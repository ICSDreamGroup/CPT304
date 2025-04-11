**Key Challenges from "No Silver Bullet[1]"**

Brooks identifies four primary inherent challenges in software engineering:

1. **Complexity： contains state complexity, function complexity and structure complexity**

   As the system grows in scale, the number of possible states increases exponentially, far beyond what developers can fully enumerate and understand, which makes it extremely difficult to predict and test the system’s conditions, directly contributing to its unreliability.

   At the same time, as the functionality becomes more complex, invoking becomes increasingly cumbersome, making it challenging for users to quickly and accurately access the desired features, thereby affecting usability.

   Moreover, the growing complexity of the software's structure means that adding and extending features often impact other parts of the system, easily leading to side effects, even affecting the stability of the whole system. In addition, complex structures often own hidden states that cannot be directly observed; if these states are not captured in a timely manner, they can become security trapdoors in the system.

2. **Conformity： refers to the requirement for a software system to adhere to external interfaces, standards, or past systems**

   If the software is the latest system to appear on the market, it needs to be compatible with existing system interfaces; Sometimes the software is considered to be the easiest to achieve conformity across a variety of existing systems. This complexity, brought about by external interface requirements, cannot be eliminated by simply redesigning the software internally.

3. **Changeability： refers to the need for the software to make corresponding adjustments according to internal and external changes**

   Software is essentially function embedded in system, and it is easier to modify than other physical products. In addition, the software is embedded in a constantly changing cultural matrix and may need to be adjusted at any time due to new needs, or other changes in the external environment.

   Successful software will inevitably undergo continuous evolution. When the software proves the practicality of its basic functions, users often apply it to new scenarios, resulting in demand for extended functions; secondly, when new computers, disks, etc. appear, the software needs to make adjustments to adapt to the new operating environment. These constant internal and external changes make the variability of software an indispensable feature.

4.  **Invisibility**： **refers to the fact that software does not have an inherent physical form**

As an abstract structure, software is different from buildings that can be visually expressed through blueprints, and needs to be represented by several directed diagrams with different representations. These diagrams are usually more complex, non-planar, and lack a natural hierarchical order. In order to manage and understand this complexity, developers usually have to artificially impose hierarchies through techniques such as "link cutting".

## Reference
[1] Brooks, Frederick P., "No Silver Bullet: Essence and     Accidents of Software Engineering," *Computer*, Vol. 20, No. 4,     April 1987, pp. 10-19.