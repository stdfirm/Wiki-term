---
title: 对象标识符(OID)缩略语-梳理研究
date: 2021-02-25 18:22:01
tags: 
	- 标准化
	- 对象标识符(OID)
	- 缩略语



---

> 来源：《对象标识符(OID)白皮书》（2015），中国电子技术标准化研究院



- AAP（Accelerated Approval Process）：快速审批过程

ITU-T 提议审批过程有两种，这是其中一种，通常在没有调整或者行政干预时使用。



- Additional secondary values：附加次级值

这是最初为定义一个弧的数值增加名字的方法，不是必须要明确，受限于 ASCII 字符，直到现在还是应用。

- Additional Unicode 标签：附加的 Unicode 标记

当 OID 树国际化时，有时需要增加一个弧标识，这个弧 标记可以采用任意 Unicode 字符，要求明确（但并不一定是唯一）。

- AFNOR: 法国标准化协会

这是法国规范化标准组织，是负责与 ISO/IEC 所有联系的法国国家实体组织。

- ANSI：美国国家标准学会 

这是美国规范化标准组织，是负责与 ISO/IEC 所有联系的美国国家实体组织。

- ASN.1（Abstract Syntax Notation 1）：抽象语法标记

主要参阅通用意义上定义的 ASN.1 标记标准，OID 工作是其中很重要的一部分内容。

- ASN.1 encodings：抽象语法标记编码

是指遵从应用标准的 ASN.1 类型（尤其是指 OID）在机器通信中的编码方式。对于任意给定的 ASN.1 规范内容来 说，有很多可能的编码方式。

- BSI：英国标准协会

这是英国规范化标准组织，是负责与ISO/IEC所有联系的英国国家实体组织。 

- CCITT：国际电报电话咨询委员会 

- CINF：子节点信息

ORS 所提供的服务之一，是指通过 DNS 解析返回子节 点（需要考虑安全隐私问题）信息的服务。

- COID：规范化 OID

ORS 所提供的服务之一，通过 DNS 解析返回一个 OID的规范化形式（全部数字）。

- COSIRA：加拿大开放系统互联注册机构 

管理加拿大国家代码的机构实体。

- CYBEX：计算机安全交互信息

ORS   所提供的服务之一，现在还在研制发展过程中，用 于信息安全领域。

- DCC：数据国家代码 

数据国家代码，参阅[b-ISO 3166-1]。 

- DNS：域名系统

这是世界范围的架构，使得 URL 被解析至相关的主机 计算机。

- DNS zone files：DNS 域目录

ORS 使用的 DNS 中技术部分内容。

- ETSI：欧洲电信标准机构

这是在SG17 的一个主要的活动组织，也可以进行OID分配。

FAQ：常见问题解答 

网页中用以提供常用帮助信息的术语。 

- ICD（International Code Designator）：国际代码指示符 

国际代码指示符，参阅[b-ISO/IEC   6523]。 

- IETF：因特网工程任务组 

因特网标准的主要管理实体之一。

- OID（International Object Identifier Tree）：国际 OID 树 一个标识的层次化树。

- IANA （Internet Assigned Numbers Authority）：互联网数 字分配机构

互联网中进行数字分配的主要机构，  尤其是管理该{iso(1) identified-organization(3) dod(6)} (1.3.6)节点下的 OID子节点分配。

- Information Object Class：信息对象分类 参阅[b-X.681]。

- Integer-valued Unicode 标签：整数值 Unicode 标记 

一个节点基本整数值的 Unicode 字符表示。 

- IRI（International Resource Identifier）：国际资源标识符 

这是一个 IETF 概念，用到了许多的“体系”。在 2010年底，一个部分被批准的体系是“OID”体系，允许  OID-IRI

值作为一个IETF OID-IRI 缀为oid）。

- ISO/IEC        （    International        Standards Organization/International Electro-Technical Commission）：国 际标准化组织/国际电工委员会

参与 ITU-T 所有联合工作（包括所有的 OID 活动）的ITU-T 建议书的管理机构。

- ITU-T（International Telecommunications Union）：国际 电信联盟

管理所有 ITU-T 建议书的组织。

- KISA（Korean Internet & Security Agency）：韩国信息安全局

这是弧 2.27({joint-iso-itu-t(2) tag-based(27)})的注册机构，也是通常 ORS 运营机构的建议机构。

- MIB（Management Information Base）: 管理信息库

这是 US DoD SNMP 工作标准化的一部分。 

- MINF（Module Information）：模块信息

ORS 所提供的服务之一，只适用于 OID 标识对象为规范 语言（典型的 ASN.1 或者 XSD）模块的情形，通过 DNS 查 询，返回该模块语法测试和机器可读的版本的接入信息。（参 阅第 18 节）

- NSEC3（Network Security 3）: 网络安全 3

DNS 的安全方案选择有很多，NSEC3 的讨论不在本手 册的范围内，但是 ORS 运营机构要求提供已验证后的NSEC3支持。

- Object Identifier Tree (OID tree)：OID 树 

- OID（Object Identifier）：对象标识符

由 ITU、ISO/IEC 联合制定的标识机制（用于任意对象）， 提供了层次化的注册机构，用以提供任意对象或者“物”的 定义。

- OID-IRI: OID 国际资源标识符

此术语不仅能够用于 ASN.1 类型，也可以用以 ASN.1 类型值所使用的标记，例如在 IETF 的“OID”IRI schema 中 使用。

- OID repository: OID 资源库

参阅[b-OID Repository]，包括一个 OID 资源库的输入/ 输出规范内容。

- ORS（OID Resolution System）：OID 解析系统

- ORS supported node：OID 支持节点

这是一个 OID 树节点，能够通过 ORS 客户端从与此节 点相关联的 DNS 上获取信息，参阅第 18 节。

- 基本整数值：基本整数值 

这是一个节点的基本标识方式，提供了 OID 树的框架，通常对于从节点到其子节点间的弧的标识是唯一而且是无

歧义的。

- RA（Registration Authority）: 注册机构

- RANS（Russian Association of Networks and Systems）： 俄罗斯网络系统协会

- RFC（Request for Comment）：请求注解 实际上为 IETF 和因特网的标准。

- RFID（Radio Frequency Identification）：射频识别 

射频识别即 RFID（Radio Frequency IDentification）技术，又称电子标签、无线射频识别，是一种通信技术，可通过无 线电讯号识别特定目标并读写相关数据，而无需识别系统与 特定目标之间建立机械或光学接触。

- RINF: 注册信息

ORS 提供的服务，通过 DNS 解析，返回节点（需要考 虑安全隐私问题）的注册信息。

- SC（Sub-Committee）：下属委员会

ISO/IEC 组织机构中的一部分。 

- SG（Study Group）：研究组

ITU-T 组织机构中的一部分，其中 SG17 进行 OID 的研 究工作。

- SNMP（Simple Network Management Protocol）：简单网络管理协议

一个很早的、广泛应用 OID 的协议，现在也在应用。

- TAP

两个 ITU-T 建议书批准过程中的一个，通常出于调整或 者管理考虑时使用。

- TINF（Tag-based   Information）：基于标签信息

由 ORS 提供的服务，根据[b-H.IRP]，提供解析节点信息 的返回（通过一个 RFID 标签请求）（参阅第 18 节）。

- TSB（Telecommunications Standardization Bureau）：电信标准化局

ITU 的顶层管理机构实体。

- TLV（Type, Length, Value）：类型、长度、值

ASN.1 最早定义的编码规则（BER 基础编码规则）的传输语法格式。

- Unicode 标签：Unicode 标签

一种在计算机上使用的字符编码，为每种语言中的每个字符设定了统一并且唯一的二进制编码，以满足跨语言、跨平 台进行文本转换、处理的要求。

此术语在 Unicode 联盟的授权下使用，指的是为 OID 树 的弧（包括长弧）标识应用的一个明确的（但不必是唯一） 名称，在 OID-IRI 标记方法中扮演着很重要的角色。

- URL（Universal Resource Locator）：通用资源定位符

IETF   中的一个很重要的术语，一般表示为“http:……” 

- XML（Extensible Mark-up Language）：可扩展标记语言

用于标记电子文件使其具有结构性的标记语言，可以用 来标记数据、定义数据类型，是一种允许用户对自己的标记 语言进行定义的源语言。XML 的编码结构即可以机读又可以 人读，应用广泛，可被多种工具支持。

- XSD（XML Schema Definition）：XML 结构定义

是另一种定义抽象语法的标记，功能覆盖了 ASN.1 的应用。虽然 规范能够应用于XML    。