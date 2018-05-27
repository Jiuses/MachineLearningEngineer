[toc]

# 说明
本项目列表是针对 Udacity 机器学习课程的项目文件列表

## P0_TitanicSurvivalExploration
在这个项目中，您将创建决策函数，并根据1912年泰坦尼克号海难的乘客特征，如：性别、年龄等，对乘客生还结果进行预测。您可以从一个简单的算法入手，然后逐渐增加该算法的复杂度，直至您至少能精确地预测出所提供数据中80%的乘客的生还结果。通过该项目，您可在正式开始学习本纳米学位前，了解机器学习的一些概念。你还可以在论坛找到该题目在 Kaggle 的[数据链接](http://discussions.youdaxue.com/t/project-0-kaggle/7032)。

此外，请确保 Python 装有完成本项目所需的程序包。我们在本项目中将使用到的 Python 库有两个，即 numpy 和 pandas。现在不需担心它们如何运作——我们将在实战项目 1 中接触到它们。本项目还将让您熟悉项目的提交程序，项目提交是您在纳米学位课程中需要完成的内容。

要开始这个项目，你可以访问我们的 GitHub 页面，或者点击这里直接下载最新的项目所需文件。

包含三个文件：

* Titanic\_Survival\_Exploration.ipynb: 这是最主要的文件，项目中的主要工作都将在这个文件上完成
* titanic\_data.csv: 项目数据表。您将需要把这个数据加载到 notebook 里。
* titanic\_visualizations.py: 这个 Python 脚本包含 helper 函数，可以让数据和存活结果可视化。

为了打开 jupyter notebook，需要完成以下几步。如果你使用 Windows 系统，你需要打开命令终端或 PowerShell；如果你使用 Mac 或者 Linux 系统，直接打开Terminal 终端即可。使用 cd 命令来打开项目文件夹。例如，在 Windows 上你可以使用 `cd C:\Users\username\Documents\` （username 用自己的用户名替换）找到项目所在的文件夹；在 Mac 上，你可以使用 `cd ~/Documents/`。在 Windows 上你可以使用 `dir` 命令，在 Mac 或者 Linux 上用 ls 命令列出当前目录中的文件和文件夹。如果发现进错目录，可以使用 `cd ..` 返回上一级目录。

一旦你进入包含项目文件的文件夹，您可以输入命令

`jupyter notebook titanic_survival_exploration.ipynb`

打开一个浏览器窗口，或者新建标签页，来使用你的 notebook。依照 notebook 上的指导回答每一个问题完成这个项目。我们还提供了随项目的 READEME 文档，上面也有关于这个项目的信息和指导。

## P1_BostonHousing

**项目概述**
在此项目中，我们将对为马萨诸塞州波士顿地区的房屋价格收集的数据应用基本机器学习概念，以预测新房屋的销售价格。您首先将探索这些数据以获取数据集的重要特征和描述性统计信息。接下来，您要正确地将数据拆分为测试数据集和训练数据集，并确定适用于此问题的性能指标。然后，您将使用不同的参数和训练集大小分析学习算法的性能图表。这让您能够挑选最好地泛化到未见过的数据的最佳模型。最后，您将根据一个新样本测试此最佳模型并将预测的销售价格与您的统计数据进行比较。

波士顿房屋市场竞争异常激烈，你想成为当地最好的房地产中介。为了与同行竞争，你决定使用几个基本的机器学习概念来帮助你和客户找到其房屋的最佳销售价格。幸运的是，你遇到了波士顿房屋数据集，其中包含大波士顿社区的房屋的各种特征的累积数据，包括其中各个地区的房屋价格的中值。你的任务是利用可用工具基于统计分析来构建一个最佳模型。然后使用该模型估算客户房屋的最佳销售价格。

**项目亮点**
此项目旨在让您熟练地在 Python 中处理数据集并使用 NumPy 和 Scikit-Learn 应用基本机器学习技术。在使用 sklearn 库中的许多可用算法之前，先练习分析和解释您模型的表现可能有所帮助。

通过完成此项目您将会学习（并最终知道）以下知识：

* 如何使用 NumPy 调查数据集的潜在特征。
* 如何分析各种学习性能图以了解方差和偏差。
* 如何确定用于从未看见的数据进行预测的最佳猜测模型。
* 如何评估模型使用之前的数据处理未看见数据的表现。

**开始项目**
要开始这个项目，你可以访问我们的 GitHub 页面，或者点击这里直接下载最新的项目所需文件。

包含三个文件：

* boston\_housing.ipynb: 这是你需要完成项目的主文件。
* housing.csv: 这是项目数据集，你需要加载到 notebook 里。
* visuals.py: 这是帮你创建数据可视化的 python 脚本。

在包含项目文件的命令行或终端下，输入命令 `jupyter notebook boston_housing.ipynb` 打开一个浏览器来开始你的项目。根据 notebook 中的项目说明来回答每一个问题。你还可以在 README 文件中看到更多项目相关的信息。

**提交项目**

优达学城的项目评审师会依据此[预测波士顿房价项目要求](https://review.udacity.com/#!/rubrics/268/view)来评审您的提交。提交前请务必确保你已经仔细查看该要求，自己也依此对照检查过了所做的项目。所有要求必须被标注为“合格”，项目才能通过。

须提交文件
提交的文件中应包含以下文件并且可以打包为单个 .zip 文件：

包含完整实现且可正常运行的代码的 “boston_housing.ipynb” 文件，并已执行所有代码块和显示了输出。
一个由jupyter notebook 导出的 **HTML** 文件，重命名为 **report.html**。此文件需同 ipynb 文件一起提交才能被审阅。
如果你已经核对过了，就可以在下一页提交项目了。

*注意*
所提交文件的文件名名，包括zip压缩包内的文件名，都不能含有中文及任何ASCII之外的字符，否则会造成提交失败。

如果你是第一次在优达学城提交项目，点击提交之后，要等1分钟左右才能打开提交页面。如果长时间打不开，可以刷新。如果依然无法打开项目提交页面，可以联系客服微信或者邮件至 support@youdaxue.com。我们正在努力修复这个问题。

## P2_FindingDonors
**项目概述**
在该项目中，你将把你学到的应用监督学习技术和分析数据的能力应用到美国人口普查收集到的数据中，来帮助一个慈善机构确定哪些人最有可能做捐助。首先你要了解普查数据是什么样的。其次，你要使用一系列数据转换和数据前处理技巧来把数据转变成可以工作的形式。你将把你选择的监督学习的算法应用在数据集上，找出最适合的算法。然后，你要优化你选出的这个模型，把他展示给慈善机构。最后，你需要深入探索这个模型以及它的预测，来看一下他对于给定的数据集表现如何。

**项目重点**
项目设计初衷是帮助你熟悉包含在 `sklearn` 中的许多监督学习的算法。同时也让你了解由一个算法构建的模型在特定数据集上的表现。在机器学习中非常重要的一点就是清楚的理解特定算法在什么情况下适用，什么情况下不适用。

完成这个项目你将学到：

* 什么情况下数据需要前处理，以及如何进行前处理。
* 如何为解决方案设定基准。
* 针对特定数据集，不同监督学习算法的表现。
* 如何为问题选择一个合适的算法。


**描述**
CharityML 是一家位于硅谷核心地带的慈善机构，它致力于为想学机器学习的学生提供经济上的帮助。在社区中发出了32000多封捐赠信之后，他们发现他们收到的每一笔捐赠，都来自年收入5万美金以上的人。为了拓展他们的捐赠池，CharityML决定向加州居民发送一封信，信只发给那些最有可能捐助的人。因为加州的工作人群有一千五百万， CharityML雇佣你来帮他们构建一个最好的算法，来识别最有可能的捐赠者以降低发送信件的成本。你的目标是评估和优化几个不同的监督学习算法来决定哪个算法能给出最高的捐赠者识别率，以降低总计的发信数量。

**软件和库**
这个项目用到下列软件和库

* [Python 2.7](https://www.python.org/download/releases/2.7/)
* [NumPy](http://www.numpy.org/)
* [pandas](http://pandas.pydata.org/)
* [scikit-learn](http://scikit-learn.org/stable/install.html)
* [matplotlib](http://matplotlib.org/)

你还需要安装和运行 [Jupyter Notebook](http://jupyter.org/)。

如果您还未安装 Python，我们强烈推荐您安装 Python 发行版：[Anaconda](http://continuum.io/downloads)，其具备包括上述程序包在内的更多程序包。安装时，确保您选择的是 Python 2.7 安装程序，而不是 Python 3.x 安装程序。

**开始项目**
要开始这个项目，你可以访问我们的 [GitHub 页面](https://github.com/nd009/finding_donors) 页面，或者点击[这里](https://github.com/nd009/finding_donors/archive/master.zip)直接下载最新的项目所需文件。建议每次最新版的notebook。

文件包含三个文件：

`finding_donors.ipynb`: 这是你需要完成项目的主文件。
`census.csv`: 这是你需要下载的数据集。
`visuals.py`: 这是为了可视化展示数据的脚本，不需要修改。

在终端或命令行，定位到包含项目文件的文件夹，输入命令 `jupyter notebook finding_donors.ipynb` 会打开一个浏览器用来编辑 notebook。按照 notebook 里面的指示回答每一个问题来完成项目。我们还以供了一个 **README** 文件，提供了一些项目需要的额外信息和指导。

**评估**
优达学城项目导师会依据此[评估准则](https://review.udacity.com/#!/rubrics/868/view)来评审您的项目。提交前请务必仔细查看此量规。所有标准必须“符合规格”才能通过。

**文件提交**
当你项目完成后，可以把文件打包成zip格式上传。需上传文件包括：

* `finding_donors.ipynb` notebook 文件，包含所有问题的回答，代码都运行无误并且运行结果都有展示。
* 一个 jupyter HTML 文件：`report.html`。你的提交里必须包含这个文件。


## P3_CreatingCustomerSegments

**项目概述**
在这个项目中，你将应用无监督学习技能研究产品花销数据。这些数据由葡萄牙里斯本的一家批发经销商收集，用于找出数据背后的客户群体。你会先选择一小部分样本，确定是否有任何产品类别是相互高度关联来进行数据研究。之后，你将通过扩展每个产品类别然后识别（和删除）不需要的异常值来进行数据预处理。有了完好的客户开支数据后，你可以对数据进行 PCA 转换，并利用聚类算法为转换后的客户数据分组。最后，你将对你发现的分组与另外的分类方式进行比较，并思考这些信息如何帮助批发经销商改善日后的服务。

**项目亮点**
此项目可以帮助你获得非监督学习的实际经验，并努力从真实的数据集中得出关于某个潜在客户的结论。如今，许多公司都在大量地收集客户和委托人的数据，并有强烈的愿望了解客户数据库背后有意义的联系。这些信息有助于公司在未来开发产品与服务，从而更好地满足客户需求。

完成此项目后，你将学到：

* 如何应用预处理技术，如特征标度和异常值检测。
* 如何阐释 PCA 处理后缩放、转换或减少的数据点。
* 如何分析 PCA 的维度，并构建一个新的特征空间。
* 如何通过优化数据集来发现数据集中的规律。
* 如何评估集群数据提供的信息，并以有意义的方式利用数据。

**项目描述**
近日，一家批发经销商尝试着针对一些客户改变其发货方式，从原来的每周五次每次早上发货，改为了更为便宜的每周三次每次晚上发货。起初，发货方式的改变并没有带来任何显著的负面结果，于是该批发商将这一更为便宜的变动推广到了所有客户。几乎同一时刻，该批发商开始收到客户对发货服务变动的投诉，也有的客户开始取消提货。该批发商受到的损失比节省下来的钱还要多。现在，该批发经销商雇佣你，希望你确定他们的客户特征和信息，以帮助它们在未来做出更加明智的商业决策。你的任务就是利用非监督学习技术，看看客户之间存在哪些相似之处，以及如何以最佳的方式将客户细分为不同类别。

**软件和库**
这个项目用到下列软件和库

* [Python 2.7](https://www.python.org/download/releases/2.7/)
* [NumPy](http://www.numpy.org/)
* [pandas](http://pandas.pydata.org/)
* [scikit-learn](http://scikit-learn.org/stable/install.html)
* [matplotlib](http://matplotlib.org/)

你还需要安装和运行 [Jupyter Notebook](http://jupyter.org/)。

如果您还未安装 Python，我们强烈推荐您安装 Python 发行版：[Anaconda](http://continuum.io/downloads)，其具备包括上述程序包在内的更多程序包。安装时，确保您选择的是 Python 2.7 安装程序，而不是 Python 3.x 安装程序。

**开始项目**
要开始这个项目，你可以访问我们的 [GitHub 页面](https://github.com/nd009/creating_customer_segments)，或者点击[这里](https://github.com/nd009/creating_customer_segments/archive/master.zip)直接下载最新的项目所需文件。建议每次提交都使用最新版的notebook。

包含三个文件：

* `customer_segments.ipynb`: 这是最主要的文件，项目中的主要工作都将在这个文件上完成
* `customers.csv`: 项目数据表。您将需要把这个数据加载到 notebook 里。
* `visuals.py`: 这个 Python 脚本包含 helper 函数，可以让数据和存活结果可视化。

在终端或命令行，定位到包含项目文件的文件夹，输入命令 `jupyter notebook customer_segments.ipynb` 会打开一个浏览器用来编辑 notebook。按照 notebook 里面的指示回答每一个问题来完成项目。我们还以供了一个 **README** 文件，提供了一些项目需要的额外信息和指导。

**项目提交**

**评估**
你的项目会由优达学城项目评审师按照 [创建客户细分项目要求](https://review.udacity.com/#!/rubrics/271/view) 进行评审。请确定你仔细阅读了该要求，并在项目提交前自我对检查。要求当中的所有条目都必须合格项目才能通过。

**提交文件**
当你准备好提交项目时，你可以把下列文件压缩成一个 zip 文件上传。

* 带有完整问题答案和代码的 `customer_segments.ipynb` `notebook` 文件。
* `notebook` 项目导出的 `HTML` 文件，命名为 `report.html`。如何导出HTML的说明在 notebook 的最下方。

当你准备好所有这些文件，并且依照项目要求核对过之后，就可以在下面的项目提交页面提交你的项目了。

**辅助材料** [Videos Zip File](http://d2uz2655q5g6b2.cloudfront.net/5422789357/P3%3A%20Creating%20Customer%20Segments%20Videos.zip)


## P4_QlearningMaze
**项目概述**

我们将会应用 Q-learning 算法完成一个经典的 Markov 决策问题 -- 走迷宫！请查看[项目详情](https://github.com/nd009/qlearning_maze)

**问题描述**
在该项目中，你将使用强化学习算法，实现一个自动走迷宫机器人。

1. 如上图所示，智能机器人显示在右上角。在我们的迷宫中，有陷阱（红色炸弹）及终点（蓝色的目标点）两种情景。机器人要尽量避开陷阱、尽快到达目的地。
2. 小车可执行的动作包括：向上走 u、向右走 r、向下走 d、向左走 l。
3. 执行不同的动作后，根据不同的情况会获得不同的奖励，具体而言，有以下几种情况。
	* 撞到墙壁：-10
	* 走到终点：50
	* 走到陷阱：-30
	* 其余情况：-0.1
4. 我们需要通过修改 robot.py 中的代码，来实现一个 Q Learning 机器人，实现上述的目标。

**完成项目流程**

1. 前往[这个链接](https://raw.githubusercontent.com/nd009/qlearning_maze/)下载项目代码。

2. 配置环境，使用 `envirnment.yml` 文件配置名为 `robot-env` 的 conda 环境，具体而言，你只需转到当前的目录，在命令行/终端中运行如下代码，稍作等待即可。`conda env create -f environment.yml`


	>安装完毕后，在命令行/终端中运行 `source activate robot-env`（Mac/Linux 系统）或 `activate robot-env`（Windows 系统）激活该环境。

3. 阅读 robot_maze.ipynb 中的指导完成项目，并根据指导修改对应的代码，生成、观察结果。

4. 导出代码与报告，上传文件，提交审阅并优化。

## P5_DogBreedClassifier
**项目概况**
欢迎来到卷积神经网络（CNN）项目！在这一项目中，你将学到如何建立一个处理现实生活中的，用户提供的图像的算法。给你一个狗的图像，你的算法将会识别并估计狗的品种，如果提供的图像是人，代码将会识别最相近的狗的品种。[项目地址](https://github.com/udacity/cn-deep-learning/tree/master/dog-project)

## P6_Capstone

**毕业项目概述**
在此毕业项目中，你将运用你在此纳米学位中学到的机器学习算法和方法选择一个你感兴趣的问题来解决。首先你需要定义(define)一个你想要解决的问题，调研可能的解决方案，并解释其衡量指标。其次，你需要通过数据可视化和数据挖掘分析 (analyze) 这个问题，以便对适于解决该问题的算法和特征有一个更好的了解。接着，你需要实现 (implement)你的算法和衡量指标。你需要记录下预处理、改善、后处理的整个过程。接下来，你需要收集这些模型的表现结果(results) ，把重要的部分可视化，来验证或证明这些结果。最后，你要在你的结果基础上得出结论 (conclusions)，讨论一下你的实现是否真的解决了这个问题。

**毕业项目要点**
我们希望通过设计这样一个项目，让你撰写一篇完整的、端到端的，针对你感兴趣问题的解决方案的报告。无论是研发新技术、从之前的技术中进行改进，学会恰当地记录你的流程，是一项对结果验证与重现而言不可或缺的技能。

通过完成该项目，你将学到：

* 如何研究和探索一个你感兴趣的真实世界的问题。
* 如何准确的运用一个特定的机器学习算法和技术。
* 如何对数据进行分析和可视化，以及如何验证结果。
* 如何把你的工作记录下来并撰写报告。

**毕业项目**
在下面这些领域中，选择一个你最感兴趣的内容，用你所学的机器学习和技术解决它。在你的报告中，如果有引用，也一定要注明出处。

* 计算机视觉
	* [猫狗大战](https://github.com/nd009/capstone/tree/master/dog_vs_cat)
	* [走神司机](https://github.com/nd009/capstone/tree/master/distracted_driver_detection)

* 自然语言处理
	* [文档归类](https://github.com/nd009/capstone/tree/master/document_classification)

* 语音识别
	* [性别语音识别](https://github.com/nd009/capstone/tree/master/Gender_Recognition_by_Voice)

* [Human or Robot](https://github.com/nd009/capstone/tree/master/human_or_robot)
* [Rossmann 销售预测](https://github.com/nd009/capstone/tree/master/Rossmann_Store_Sales)

无论你最终选择了哪个领域的问题，你都需要用5个主要步骤来完成这个项目，并把步骤记录下来。从问题的定义，到做出一个解决方案。每个步骤在这整个过程中都扮演了非常重要的角色。在你完成项目的过程中，记得要为你的项目报告打草稿，这也是你项目提交的最重要的方面。

要查看你的项目和问题是否符合优达学城机器学习毕业项目的要求，请查看这个[评判标准](https://review.udacity.com/#!/rubrics/273/view)。把这些标准记下来。必须符合平板标准中的所有要求，才能算作一个令人满意的报告。

**报告指南**
这个项目将依照你提交的书面报告来评估。此外，如果项目需要，其他材料例如数据集也需要被评估。我们要求开题报告需要包含足够的细节、文档、分析以及你对如何完成这个项目的想法的讨论。也正是因为这个原因，按照一个专业标准来撰写报告就显得尤为重要。这可以让每一个审阅你项目提交的人，都可以清晰的找到组成你报告的每一个部分。如果没有按照这个要求写，你的报告可能不会得到充分的审阅。我们特地为你准备了一个[开题报告模版](https://github.com/nd009/capstone/blob/master/capstone_proposal_template.md)，帮助你了解开题报告的结构。同时我们建议的开题报告长度为2到3页。

机器学习毕业项目报告应当与学院里的研究报告没有区别。你的目标是呈现一个你选择的特定问题领域内的研究发现，把项目完成过程中的每一个步骤都记录下来。具体描述可见[开题报告模版](https://github.com/nd009/capstone/blob/master/capstone_proposal_template.md) 。它提供了一个 *报告核对单*，可以帮你完成这个报告。请利用好这个资源！

**提交项目**
注意⚠️：由于中英文版本对毕业项目的要求不同，如果你选择中文版本的选题，请确保一定要在中文页面中提交。

**评审**
你的项目会由优达学城项目评审师依照[毕业项目开题报告要求](https://review.udacity.com/#!/rubrics/484/view)来评审。请确定你已完整的读过了这个要求，并在提交前对照检查过了你的项目。提交项目必须满足所有要求中每一项才能算作项目通过。

**提交文件**
你的提交最少需要包括下列要求的文件。如果你用 zip 压缩包来提交，请注意总的文件大小。你的提交需要包括：

* 一个名为 `proposal.pdf` 的项目报告（只接受 pdf 格式），里面包含了开题报告要求的七个要素。建议的报告长度是2到3页。
* 任何额外的支持材料，例如数据集、图片或者项目开发和实现所必需的输入文件。如果这些文件太大，无法提交。也请在你的 `README` 文件中提供一个合适的获取方法。

注意：所提交文件的文件名名，包括zip压缩包内的文件名，都不能含有中文及任何 ASCII 之外的字符，否则会造成提交失败。

当这些文件你都整理好，并且已经对照项目要求检查过。可以在项目提交页面进行提交。
