# 2021
The prevailing distributed computing model of the curent era is called ctiem servar computing.A (Client/Server system)
is a solution in which the presentation.presentatoanaogic,application logic, data manipulation and data layers are
distributed between client PCs and one or more servers. A ( Thin Client) is a personal computer that does not have to be very powerful in terms of processor speed and memory because it only presents the interface to the user. A (Fat Client) is a personal
computer, notebook.computer, or workstation that is typically more powerfil in terms of processor
speed,memory, and storage capacity. A (Database server) hosts one or more shamad database but also executes all
database commands and services for information systems.A (n) (Web server) hosts Internet or intranet web
sites,it communicates with clients by returning to them documents and data.

<details>
<summary>翻译</summary>

现在主流的分布式计算是客户/服务器计算模式。客户/服务器系统是一种解决方案，其中表示层、表示逻辑层、应用逻辑、数据操作、数据层分布在客户的PC端与一个或多个服务器端之间。瘦客户端指的是个人电脑在处理速度、内存方面无须很强大，因为它仅仅是展示接口给用户。胖客户端是指个人电脑、笔记本、工作站在处理速度、内存、存储容量方面都很强大的一类电脑。数据库服务器控制一个或多个共享数据库，同时也执行所有数据库命令以及服务于信息系统。web服务器控制互联网、信息平台，与客户端通信，返回给客户端文件与数据。
</details>

# 2018
Designing the data storage architecture is an important activity in system design. There are two main types of data storage formats: files and databases. Files are electronic of data that have been optimized to perform a particular transaction. There are several types of files that differ in the way they are used to support an application.（ Master files ） store core information that is important to the business and , more specifically , to the application , such as order information or customer mailing information . （ Look-up files） contain static values , such as a list of valid codes or the names of cities . Typically, the list is used for validation. A database is a collection of groupings of information that are related to each other in some way. There are many different types of databases that exist on the market today.（ Legacy database ） is given to those databases which are based on older , sometimes outdated technology that is seldom used to develop new applications . （ Hierarchical database ） are collections of records that are related to each other through pointers In relational database , （ referential integrity ） can be used in ensuring that values linking the tables together through the primary and foreign keys are valid and correctly synchronized.

<details>
设计数据存储架构是系统设计中的一项重要活动。数据存储格式有两种主要类型：文件和数据库。文件是优化以执行特定交易数据的电子数据。有几种类型的文件在用于支持应用程序的方式上有所不同。（71 主文件）存储的核心信息对业务很重要，更具体地说，对应用程序而言，例如订单信息或客户邮件信息。（72 查找文件）包含静态值，例如有效代码列表或城市名称。通常，该列表用于验证。数据库是以某种方式彼此相关的信息分组的集合。目前市场上存在许多不同类型的数据库。（73 旧数据库）给予那些基于较旧的，有时过时的技术的数据库，这些技术很少用于开发新的应用程序。 （74 层次数据库）是通过指针彼此相关的记录集合在关系数据库中，（75 参照完整性）可用于确保通过主键和外键将表链接在一起的值是有效且正确同步的。
</details>

# 2017
The architecture design specifies the overall architecture and the placement of software and hardware that will be used. Architecture design is a very complex process that is often left to experienced architecture designers and consultants. The first step is to refine the ( nonfunctional requirements ) into more detailed requirements that are then employed to help select the architecture to be used and the software components to be placed on each device. In a ( client-server architecture ), one also has to decide whether to use a two-tier, three-tier, or n-tier architecture. Then the requirements and the architecture design are used to develop the hardware and software specification. There are four primary types of nonfunctional requirements that can be important in designing the architecture. ( Operational requirements ) specify the operating environment(s) in which the system must perform and how those may change over time. ( Performance requirements ) focus on the nonfunctional requirements issues such as response time, capacity, and reliability. ( Security requirements ) are the abilities to protect the information system from disruption and data loss, whether caused by an intentional act. Cultural and political requirements are specific to the countries in which the system will be used.

<details>
架构设计指定了将要使用的软件和硬件的总体架构和布局。 架构设计是一个非常复杂的过程，往往留给经验丰富的架构设计师和顾问。 第一步是将（71 非功能性需求）细化为更详细的要求，然后用于帮助选择要使用的体系结构以及要放置在每个设备上的软件组件。在（72 客户端-服务器架构）中，还必须决定是使用两层，三层还是n层架构。 然后使用需求和体系结构设计来开发硬件和软件规范。 有四种主要的非功能需求类型可能在设计架构时非常重要。 （73 运维需求）指定系统必须执行的操作环境以及这些操作环境如何随时间变化。 （74 性能需求）侧重于非功能性需求问题，如响应时间，容量和可靠性。 （75 安全需求）是否有能力保护信息系统免受故意行为造成的破坏和数据丢失。 文化和政治要求是特定于系统将被使用的国家。
</details>

# 2016 & 2015
The objective of （ architecture design ）is to determine what parts of the application software will be assigned to what hardware. The major software components of the system being developed have to be identified and then allocated to the various hardware components on which the system will operate. All software systems can be divided into four basic functions. The first is（ data storage ）. Most information systems require data to be stored and retrieved, whether a small file, such as a memo produced by a word processor, or a large database, such as one that stores an organization’s accounting records. The second function is the （ dataaccess logic ）,the processing required to access data, which often means database queries in Structured Query Language. The third function is the （ application logic ）,which is the logic documented in the DFDs, use cases, and functional requirements. The fourth function is the presentation logic, the display of information to the user and the acceptance of the user’s commands. The three primary hardware components of a system are （ clients, servers, and network ）.

架构设计的目标是确定应用软件的哪些部分将分配到何种硬件。识别出正在开发系统的主要软件构件并分配到系统将要运行的硬件构件。所有软件系统可分为四项基本功能。第一项是数据存储。大多数信息系统需要数据进行存储并检索，不论是一个小文件，比如一个字处理器产生的一个备忘录，还是一个大型数据库，比如存储一个企业会计记录的数据库。第二项功能是数据访问逻辑，处理过程需要访问数据，这通常是指用SQL进行数据库查询。第三项功能是应用程序逻辑，这些逻辑通过数据流图，用例和功能需求来记录。第四项功能是表示逻辑，给用户显示信息并接收用户命令。一个系统的三类主要硬件构件是客户机、服务器和网络。

#2014
Software architecture reconstruction is an interpretive, interactive, and iterative process including many activities. （ Information extraction ）involves analyzing a system's existing design and implementation artifacts to construct a model of it. The result is used in the following activities to construct a view of the system. The database construction activity converts the （ elements and relations ） contained in the view into a standard format for storage in a database. The （ view fusion ）activity involves defining and manipulating the information stored in database to reconcile, augment, and establish connections between the elements. Reconstruction consists of two primary activities: （ visualization and interaction ） and （ pattern definition and recognition ）. The former provides a mechanism for the user to manipulate architectural elements, and the latter provides facilities for architecture reconstruction.

软件架构重构是一个解释性、交互式和反复迭代的过程，包括了多项活动。信息提取通过分析系统现有设计和实现工件来构造它的模型。其结果用于在后续活动中构造系统的视图。数据库构建活动把模型中包含的元素和关系转换为数据库中的标准存储格式。视图融合活动包括定义和操作数据库中存储的信息，理顺、加强并建立起元素之间的连接。重构由两个主要活动组成；可视化和交互记及模式定义和识别。前者提供了一种让用户操作架构元素的机制，后者则提供了用于架构重构的设施。

2013
A system's architecture is a representation of a system in which there is a mapping of（functionality ）onto hardware and software components, a mapping of the（ software architecture）onto the hardware architecture. and a concern for the human interaction with these components. That is, system architecture is concerned with a total system, including hardware. software, and humans.

Software architectural structures can be divided into three major categories, depending on the broad nature of the elements they show.

1）（ Module structures）embody decisions as a set of code or data units that have to be constructed or procured.

2）（ Component-and-connector structures）embody decisions as to how the system is to be structured as set of elements that have runtime behavior and interactions.

3）（Allocation structures ）embody decisions as to how the system will relate to nonsoftware structures in its environment(such as CPUs, file systems, networks, development teams, etc.).

系统架构是一个系统的一种表示，包含了功能到软硬件构件的映射、软件架构到硬件架构的映射以及对于这些组件人机交互的关注。也就是说，系统架构关注于整个系统，包括硬件、软件和使用者。软件架构结构根据其所展示元素的广义性质，可以被分为三个主要类别。

1）模块结构将决策体现为一组需要被构建或采购的代码或数据单元。

2）构件连接器结构将决策体现为系统如何被结构化为一组具有运行时行为和交互的元素。

3）分配结构将决策体现为系统如何在其环境中关联到非软件结构，如CPU、文件系统、网络、开发团队等。

# 2012
An application architecture specifies the technologies to be used to implement one or more information systems． It serves as an outline for detailed design， construction， and implementation． Given the models and details， include（ logical DFDs and ERD ）， we can distribute data and processes to create a general design of application architecture． The design will normally be constrained by architecture standards， project objectives， and （ the feasibility of techniques used ）． The first physical DFD to be drawn is the（ network architecture DFD ）． The next step is to distribute data stores to different processors． Data（ partitioning and replication ） are two types of distributed data which most RDBMSs support． There are many distribution options used in data distribution． In the case of （ storing specific tables on different servers ）we should record each table as a data store on the physical DFD and connect each to the appropriate server．

应用架构说明了实现一个或多个信息系统所使用的技术，它作为详细设计、构造和实现的一个大纲。给定了包括逻辑数据流图和实体联系图在内的模型和详细资料，我们可以分配数据和过程以创建应用架构的一个概要设计。概要设计通常会受到架构标准、项目目标和所使用技术的可行性的制约。需要绘制的第一个物理数据流图是网络架构数据流图。接下来是分配数据存储到不同的处理器。数据分区和复制是大多数关系型数据库支持的两种分布式数据形式。有许多分配方法用于数据分布。在不同服务器上存储特定表的情况下，我们应该将每个表记为物理数据流图中的一个数据存储，并将其连接到相应的服务器。

# 2011
Information systems design is defined as those tasks that focus on the specification of a detailed computer-based solution. Typically， there are four systems design tasks for in-house development.

1) The first task is to specify （ an application architecture ）， which defines the technologies to be used by one， more， or all information systems in terms of their data， processes， interfaces， and network components. This task is accomplished by analyzing the data models and process models that are initially created during requirements analysis.

2) The next systems design task is to develop the （ database design specifications ） . The purpose of this task is to prepare technical design specifications for a database that will be adaptable to future requirements and expansion.

3) Once the database prototype has been built， the systems designer can work closely with system users to develop input， output and dialogue specifications. The（ internal controls ） must be specified to ensure that the outputs are not lost， misrouted， misused， or incomplete.

4) The fourth design task involves packaging all the specifications from the previous design tasks into a set of specifications that will guide the（ computer programmer’s ） activities during the following phases of the systems development methodology.

Finally， we should（ reevaluate project feasibility ）and update the project plan accordingly. The key deliverable should include a detailed plan for the construction phase that should follow.

信息系统设计被定义为一些任务，它们主要关注一个详细的计算机解决方案的规格说明。通常来说，内部开发有四种系统设计任务。

（1）第一项任务是确定一个应用程序架构，它以数据、过程、接口和网络组件的方式定义一个、多个或所有信息系统要使用的技术。完成这项任务需要分析最初创建于需求分析期间的数据模型和过程模型。

（2）下一项系统设计任务是开发数据库设计的规格说明。该任务的目的是准备一个数据库技术设计规格说明，以适应将来的需求和扩展。

（3）一旦建成了数据库原型，系统设计入员能够和系统用户密切合作开发输入、输出和对话框规格说明。必须指定内部控件来确保输出不会丢失、误传、滥用或不完整。

（4）第四项设计任务包括把之前所有设计任务的规格说明打包为一套规格说明，将在系统开发方法的后续阶段中指导计算机程序员的活动。

最后，我们应该重新评估项目的可行性并相应地更新项目计划。主要交付成果将包括构建阶段应该遵循的一个详细计划。

# 2010
The software architecture is a set of software components， subsystems， relationships， interactions， the properties of each of these elements， and the set of guiding principles that together constitute the fundamental properties and constraints of a software system or set of systems.（ Architectural pattern ） defines a general set of element types and their interactions. The examples include Pipes and Filters, Model-View-Controller, and Reflection. A （ model ） in software architecture is a representation used to understand or document one or more aspects of a problem or solution. Architecture is usually used in conjunction with many adjunct terms.The （ business architecture ）defines the key strategies， organization， goals and related processes of the enterprise.At the enterprise level， the （ application architecture ） may be more of a set of guidelines on how the various software architectures should be constructed consistently across the enterprise.The （ reference architecture ）， which describes the high-level set of elements involved in application from a particular domain along with their interactions， is often used to focus on subsystem definition rather than application process level definition.

软件架构是一组软件构件、子系统、关联关系、交互关系以及其中每个元素的特性和一组指导原则，这些共同构成一个软件系统或一组系统的基本特性和约束。架构模式定义了一组通用的元素类型及其交互关系。其中的例子包括Pipes and Filters、MVC和Reflection。软件架构中的模型是一种表现形式，用于从一个或多个方面理解或记录一个问题或解决方案。架构通常会与一些附属词结合起来使用。业务架构定义了企业的关键策略、组织、目标和相关过程。在企业层面，应用架构可能更多的是一组关于应该如何在整个企业一致地构建各种软件架构的指导原则。参考架构描述了源自特定领域的应用涉及的高层元素集合及其交互关系，通常用于关注子系统的定义而不是应用过程级别定义。

#2009 
An architectural style defines as a family of such systems in terms of a（pattern）of structural organization．More specifically， an architectural style defines a vocabulary of （components）and connector types， and a set of （constraints） on how they can be combined. For many styles there may also exist one or more （semantic models）that specify how to determine a system’s overall properties from the properties of its parts．Many of architectural styles have been developed over the years.
The best-known examples of（pipe-and-filter）architectures are programs written in the Unix shell.

一种架构风格以一种结构化组织模式定义一组这样的系统。具体来说，一种架构风格定义了一个构件及连接器类型的词汇表，以及一组关于它们如何能够被关联的约束对于许多风格来说，可能也存在一个或多个语义模型，从系统部件的特性来确定系统的整体特性。许多架构风格已经发展了很多年。
众所周知的管道-过滤器架构的例子就是用UNIX shell编写的程序。
