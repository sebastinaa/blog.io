---
layout: post
title: 电路原理图的学习步骤
date: 2017-11-06
categories: blog
tags: [电路原理图]
description: Email:Jning@beamer.top
---

一、电子电路的意义

    电路图是人们为了研究和工程的需要，用约定的符号绘制的一种表示电路结构的图形。通过电路图可以知道实际电路的情况。这样，我们在分析电路时，就不必把实物翻来覆去地琢磨，而只要拿着一张图纸就可以了。在设计电路时，也可以从容地纸上或电脑上进行，确认完善后再进行实际安装，通过调试、改进，直至成功。我们更可以应用先进的计算机软件来进行电路的辅助设计，甚至进行虚拟的电路实验，大大提高工作效率。

二、电子电路图的分类

    常遇到的电子电路图有原理图、方框图、装配图和印版图等。

   1、原理图

   原理图就是用来体现电子电路的工作原理的一种电路图，又被叫做“电原理图”。这种图由于它直接体现了电子电路的结构和工作原理，所以一般用在设计、分析电路中。分析电路时，通过识别图纸上所画的各种电路元件符号以及它们之间的连接方式，就可以了解电路的实际工作情况。下图所示就是一个收音机电路的原理图。

   2、方框图(框图)

   方框图是一种用方框和连线来表示电路工作原理和构成概况的电路图。从根本上说，这也是一种原理图。不过在这种图纸中，除了方框和连线几乎没有别的符号了。它和上面的原理图主要的区别就在于原理图上详细地绘制了电路的全部的元器件和它们的连接方式，而方框图只是简单地将电路安装功能划分为几个部分，将每一个部分描绘成一个方框，在方框中加上简单的文字说明，在方框间用连线(有时用带箭头的连线)说明各个方框之间的关系。所以方框图只能用来体现电路的大致工作原理，而原理图除了详细地表明电路的工作原理外，还可以用来作为采集元件、制作电路的依据。下图所示的就是上述收音机电路的方框图。

   3.装配图

   它是为了进行电路装配而采用的一种图纸，图上的符号往往是电路元件的实物的外形图。我们只要照着图上画的样子，依样画葫芦地把一些电路元器件连接起来就能够完成电路的装配。这种电路图一般是供初学者使用的。

   装配图根据装配模板的不同而各不一样，大多数作为电子产品的场合，用的都是下面要介绍的印刷线路板，所以印板图是装配图的主要形式。

   在初学电子知识时，为了能早一点接触电子技术，我们选用了螺孔板作为基本的安装模板，因此安装图也就变成另一种模式。

   4.印板图

   印板图的全名是“印刷电路板图”或“印刷线路板图”，它和装配图其实属于同一类的电路图，都是供装配实际电路使用的。

   印刷电路板是在一块绝缘板上先覆上一层金属箔，再将电路不需要的金属箔腐蚀掉，剩下的部分金属箔作为电路元器件之间的连接线，然后将电路中的元器件安装在这块绝缘板上，利用板上剩余的金属箔作为元器件之间导电的连线，完成电路的连接。由于这种电路板的一面或两面覆的金属是铜皮，所以印刷电路板又叫“覆铜板”。印板图的元件分布往往和原理图中大不一样。这主要是因为，在印刷电路板的设计中，主要考虑所有元件的分布和连接是否合理，要考虑元件体积、散热、抗干扰、抗耦合等等诸多因素，综合这些因素设计出来的印刷电路板，从外观看很难和原理图完全一致;而实际上却能更好地实现电路的功能。

   随着科技发展，现在印刷线路板的制作技术已经有了很大的发展;除了单面板、双面板外，还有多面板，已经大量运用到日常生活、工业生产、国防建设、航天事业等许多领域。

   在上面介绍的四种形式的电路图中，电原理图是最常用也是最重要的，能够看懂原理图，也就基本掌握了电路的原理，绘制方框图，设计装配图、印板图这都比较容易了。掌握了原理图，进行电器的维修、设计，也是十分方便的。因此，关键是掌握原理图。

   三、电路图的组成

   电路图主要由元件符号、连线、结点、注释四大部分组成。

   元件符号表示实际电路中的元件，它的形状与实际的元件不一定相似，甚至完全不一样。但是它一般都表示出了元件的特点，而且引脚的数目都和实际元件保持一致。

   连线表示的是实际电路中的导线，在原理图中虽然是一根线，但在常用的印刷电路板中往往不是线而是各种形状的铜箔块，就像收音机原理图中的许多连线在印刷电路板图中并不一定都是线形的，也可以是一定形状的铜膜。

   结点表示几个元件引脚或几条导线之间相互的连接关系。所有和结点相连的元件引脚、导线，不论数目多少，都是导通的。

   注释在电路图中是十分重要的，电路图中所有的文字都可以归入注释—类。细看以上各图就会发现，在电路图的各个地方都有注释存在，它们被用来说明元件的型号、名称等等。

   若不知电路的作用，可先分析电路的输入和输出信号之间的关系。如信号变化规律及它们之间的关系、相位问题是同相位，或反相位。电路和组成形式，是放大电路，振荡电路，脉冲电路，还是解调电路。电器修理、电路设计的工作人员都是要通过分析电路原理图，了解电器的功能和工作原理，才能得心应手开展工作的。作为从事此项工作的技术人员，首先要有过硬的基本功，要能对有技术参数的电路原理图进行总体了解，能进行划分功能模块，找出信号流向，确定元件作用。要学会维修电器设备和设计电路，就必须熟练掌握各单元电路的原理。会划分功能块，能按照不同的功能把整机电路的元件进行分组，让每个功能块形成一个具体功能的元件组合，如基本放大电路，开关电路，波形变换电路等。

   要掌握分析常用电路的几种方法，熟悉每种方法适合的电路类型和分析步骤。

  1、交流等效电路分析法首先画出交流等效电路，再分析电路的交流状态，即：电路有信号输入时，电路中各环节的电压和电流是否按输入信号的规律变化、是放大、振荡，还是限幅削波、整形、鉴相等。

  2、直流等效电路分析法画出直流等效电路图，分析电路的直流系统参数，搞清晶体管静态工作点和偏置性质，级间耦合方式等。分析有关元器件在电路中所处状态及起的作用。例如：三极管的工作状态，如饱和、放大、截止区，二极管处于导通或截止等。

  3、频率特性分析法主要看电路本身所具有的频率是否与它所处理信号的频谱相适应。粗略估算一下它的中心频率，上、下限频率和频带宽度等，例如：各种滤波、陷波、谐振、选频等电路。

  4、时间常数分析法主要分析由R、L、C及二极管组成的电路、性质。时间常数是反映储能元件上能量积累和消耗快慢的一个参数。若时间常数不同，尽管它的形式和接法相似，但所起的作用还是不同，常见的有耦合电路、微分电路、积分电路、退耦电路、峰值检波电路等。

 最后，将实际电路与基本原理对照，根据元件在电路中的作用，按以上的方法一步步分析，就不难看懂。当然要真正融会贯通还需要坚持不懈地学习，有了一定的理论后分析电路图就不费力了。

 四、电路图的定义：

 电路图，是通过电路元件符号绘制的电子元件连线走向图，它详细的描绘了各个元件的连线和走向，各个引脚的说明，和一些检测数据。

 原理图，又被叫做“电原理图”。这种图，由于它直接体现了电子电路的结构和工作原理，所以一般用在设计、分析电路中。分析电路时，通过识别图纸上所画的各种电路元件符号，以及它们之间的连接方式，就可以了解电路的实际工作。原理图就是用来体现电子电路的工作原理的一种电路情况。

  PCB图，是电路板的映射图纸，它详细描绘了电路板的走线，元件的位置等。

 看电路图首先看电源部分，理解电路在什么电源的情况下工作，交流还是直流，单电源还是多电源及电压等级。清楚了以后看分部电路，先区别是数字电路，还是模拟电路，模拟电路看信号采集，搞清楚信号来源，有射频、音频、各类传感器、仪器仪表或其他电路等，分析信号是交流、直流还是脉冲，属电压型还是电流型。分析后续电路的功能，弄清是解调、放大、整形还是补偿等作用。最后看输出电路，是调制还是驱动。数字电路则主要分析电路的逻辑功能和作用。

  要看懂电路板，那首先最好是要能看懂它的电原理图(即电路图)，掌握电子元器件的标示方式和它的工作原理，掌握一些常用的元器件的正常的参数和在正常的电路中所起到的作用等等知识，然后再对电路板(称为印刷线路板)进行分析，就能比较快的看懂它的工作原理和一些需要掌握的情况了。

 分子电路模块，再找个子电路的核心元件(当然要熟悉这个元件)找出各子电路模块之间电气量的联系，最后是整个电路的输出和输入或者说是功能。

  整机电路是有一定的功能的，是由各单元电路组成，单元电路组成具有一定功能的信号处理支路，再由这些支路电路组成整机电路。先要搞清你看的电路图的作用中什么,是属于那一类的电路,是音频、视频、数字、还是混合电路，再用相应的单元电路知识去解读这些电路，同时要从交流信号层面、直流层面进行分析，电路直流部分是电路正常工作的基础，交流信号是在直流电路正常后才能得到相应的处理，电路没有良好的直流状态，是不能正常工作的。还要从频率层面、放大器的增益层面进行分析，不同频率的信号在经过电路处理时，由于电路中非线性元件的原因，会对不同频率有不同的处理结果，放大器对不同频率的信号也的不同的放大能力，电路在设计时会对所需要的频率信号进行有目的的处理，从而达到机器功能上的需要。再有就是要分析各单元电路之间的关系，以及单元电路间的输入、输出的关系。交流信号经过这些电路后产生了怎样的变化等等。在了解了各条支路的工作原理后，才能分析出整机的工作原理，有时各支路电路间也存在信号的交连，例如电视机的行输出电路的行逆程脉冲就用于色解码电路，行输出电路与色解码电路存在信号的相互连系，这时可以将这些支路理解为另一种单元电路，再对它们进行分析。

  我想这里面有个顺序问题：比如对高频电路，首先应该掌握电路的功能和输入、输出关系，有了总体的把握后，好比是抓住了牛鼻子，因为虽然电路不同，器件不同，但他们的输入、输出关系频谱是不会变的。然后再分析实现这样功能变换的基本原理和方法，具体到部分的分析。

  进行电路设计是要通过分析电路原理图入手，但必须首先了解所需芯片的引脚及基本的作用，这样有利于更好的了解电路的工作原理，这样才能应用于自己的电路，有利于进行电路的裁剪和扩展。在进行电路分析时，首先对电路原理图有一个总体的了解，划分出各个功能模块，如电源模块，控制器模块，存贮器模块，音频模块，GPRS模块等。各个模块逐一分析，最后统一起来看就可大体了解电路所要实现的功能了。设计电路时，最好熟练掌握常见或者常用的单元电路的原理，如电源模块，稳压模块，存贮器模块等，常用的芯片，如：7805，7812等。

 进行电路设计时，要将自己所要设计的电路划分成几个模块，这样分别设计在不同的原理图里，最后进行整合。电路中有信号输入时，各个基本点的电压是多少，电流是多少，要有个粗略的估计。对于有放大器，R、L、C的电路，要看是否是振荡电路，放大电路，还是整形电路等。

 晶体管的静态工作点的分析，工作状态的分析等，电容的滤波，级间耦合，高频，低频电路等。一般我们用的是低频电路，高频一般是通信方面用的比较多。

  进行自我分析和自我设计后，就会对电路的基本原理有多了解和掌握了，对自己在以后的设计中积累了设计与调试的经验。当然真正的熟练还需磨练啊！

























---

[关于我](http://beamer.top/about/)

这里有我的个人简介：[关于我](http://beamer.top/about/)

如果你想看到我最新的文章，可以关注我的另一个私人博客「lemaden520」[点此进入](https://liuning.vip/)。