# 使用 Excel 中的 Microsoft 365 Copilot 为数据设置格式、排序、筛选和突出显示内容

借助 Excel 中的 Microsoft 365 Copilot，可以轻松对表格进行突出显示、排序和筛选，以快速聚焦于对你重要的内容。 对于 Excel 中的单个表，Copilot 处理起来毫不费力：

- 数据的排序与筛选。

- 简单条件格式之应用。

要开始，请将数据格式化为[支持的格式](https://support.microsoft.com/topic/format-data-for-copilot-in-excel-1604c8eb-57f1-4db1-8363-d53336228c65)，然后选择功能区中的 **Copilot** 按钮。 然后，告知 Copilot 如何调整，以便数据部分能更好被查看。

在以下示例中，我们从简单的提示开始，然后在此过程中添加元素。 按照示例使用自己的数据进行操作。

## 我们开始撰写

首先，下载 **_[Fabrikam Q1 marketing campaigns.xlsx](https://go.microsoft.com/fwlink/?linkid=2269124)_**，如果尚未保存，请将该文件保存到 **OneDrive 文件夹**中。

在 Excel 中打开电子表格，然后通过选择功能区“**开始**”选项卡中的 Copilot 图标打开 **Copilot** 窗格。输入下面的提示，然后继续操作。

> [!NOTE]
> 启动撰写提示：
>
> _对此表进行排序。_

在这个简单的提示中，从基本**目标**开始：_对 Excel 表进行排序和筛选_。 但是，没有说明你希望如何对数据进行排序以及要筛选哪个字段。

| 元素 | 示例 |
| :------ | :------- |
| **基本提示：** 从一个“**目标**”开始 | **_对此表进行排序..._** |
| **良好提示：** 添加“**上下文**” | 添加**上下文**可以帮助 Copilot 了解幻灯片的用途以及要关注的主题。 _“...寻找最具影响力的销售员。”_ |
| **更好的提示：** 指定“**来源**” | 假定此提示的**来源**是我们在 Excel 中使用的表。 _“...此表 [Table1]...”_ |
| **最佳提示：** 设置明确的“**预期**” | 最后，添加**期望**可以帮助 Copilot 了解你希望如何对表进行排序、筛选和呈现。 _“并根据净收入突出显示排名最靠前和最靠后的市场活动负责人。”_ |

> [!NOTE]
> **精心制作的提示：**
>
> _对此表 [表 1] 进行排序以查找最具影响力的销售员，并根据净收入突出显示排名最靠前和最靠后的市场活动负责人_

此提示需要执行多个步骤，这是一种称为**链接**的提示技术，你可以要求 Copilot 执行一系列连续的命令来实现单个目标。

**第一个提示**：

```text
Sort this table [Table1] to look for the most impactful salesperson.
```

**第二个提示**：

```text
highlight the top and bottom campaign owners based off of net revenue
```

有了此提示中的**目标**、**上下文**、**来源**和**期望**，Copilot 就具备了为你提供可靠答案所需的所有信息。

## 浏览更多

尝试以下简单的提示以突出显示、排序和筛选数据，并添加其他元素以改进结果：

- 在“销售”列中加粗前10个值。

- 突出显示“销售量”中最大值。

- 将参与率从小到大排序。  

- 筛选出下周到期的项目。

> [!IMPORTANT]
> Copilot 仅适用于存储在 OneDrive 或 SharePoint 上的文件。 如果无法在功能区中选择 Copilot 按钮，请尝试先将文件保存到云。 有关详细信息，请参阅[使用 Excel 中的 Copilot 对数据进行突出显示、排序和筛选](https://support.microsoft.com/office/highlight-sort-and-filter-your-data-with-copilot-in-excel-05302e3f-de42-4475-b235-be9cb3d4e936)。
