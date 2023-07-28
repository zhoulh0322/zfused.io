制片常用部分功能快速上手

## 界面切换
在涉及到任务环节的实体模块（资产/场景/镜头）可以切换显示模式，以满足不同需求下的视图显示
+ **行列**：以行列模式显示实体下的所有环节任务，方便直观的看到单实体的环节和任务情况
    点击实体前的箭头可以展开查看所有相关环节任务，在这里可以快速查看或修改任务信息  

![](../images/quick_start/producer/show_mode_row.png ':size=900')

+ **竖列**：以竖列模式显示实体下的所有环节任务，方便同时一览所有实体的环节和任务情况
    点击环节名称左端的箭头可以展开查看单环节任务

![](../images/quick_start/producer/show_mode_column.png ':size=900')

+ **甘特图**：显示任务甘特图

![](../images/quick_start/producer/show_mode_gante.png)

## 实体新建（资产/场景/镜头）
在对应模块下点击左上角的`创建资产`/`创建场景`/`创建镜头`，状态默认选择为激活，
+ 在创建镜头前需要提前创建好场次，可以没有集信息，但必须要有场次信息
+ 如果状态一栏为空白则无法成功创建，需要联系我方技术人员配置相关状态

![](../images/quick_start/producer/entity_create.png)

## 环节新建
新建环节涉及到流程传递，需要联系zFused官方技术人员创建部署

## 任务创建
涉及到任务环节的实体模块（资产/场景/镜头）可以创建任务，三者创建方式相同，在对应模块下操作即可，以资产为例：
+ **常规创建**
  1. 点击对应模块，以资产任务为例即点击资产
  2. 在实体上点击小眼睛打开实体详情
  3. 选择实体任务栏
  4. 勾选要创建任务的环节，支持多选
  5. 勾选后会弹出任务设置界面，再这里可以设置任务信息，比如制作人员

    ![](../images/quick_start/producer/task_create.png)
+ **快捷创建**
  1. 点击对应模块，以资产任务为例即点击资产
  2. 切换显示模式为竖列，可以同时列出多个资产的环节任务情况
  3. 找到要创建任务的资产
  4. 找到要创建任务的环节，点击左侧箭头展开环节信息
  5. 在对应资产的对应环节处，点击加号`十`，即可创建出该资产的对应任务，支持多选资产同时创建
    
    ![](../images/quick_start/producer/task_create_quick.png)

## 项目人员添加
处于环节内的成员才可以领取该环节任务，成员在添加到环节时会自动添加到总项目成员内，不需要再次添加
1. 点击`项目` - `设置`
2. 选择`项目成员`
3. 筛选环节
4. 面板内展示的是目前所有该环节内的成员
5. 手动添加成员可以点击`添加用户`，在弹出的面板中搜索用户，支持中英文关键字搜索和多选，在目标用户上双击或点击面板中央的右键头 `>` ，将用户添加到已选择用户中，点击确认即可添加
6.  批量添加成员可以点击`添加所有用户`，可以一键添加所有的用户，或按照部门批量添加，部门成员设置详见[部门设置](/desktop/member/department.md#部门人员)

![](../images/project/project/member_link.png)

制片等不属于某些具体环节的统筹人员，可以添加到项目成员内，在界面的下方点击添加用户即可
![](../images/quick_start/producer/member.png ':size=900')


## 任务分配人员
+ 内部人员分配
找到任务详情部分的`指定人员`列，点击人物图标，即可在弹出的界面中选择制作人员将任务分配给他，下图分别为行列与竖列显示模式下，人员指定的位置
    > 如果指定用户界面中找不到目标人员，请先确认该用户是否被添加到该项目的环节成员中

    ![](../images/quick_start/producer/task_assign.png ':size=900')
    ![](../images/quick_start/producer/task_assign2.png ':size=900')
+ 供应商分配
找到任务详情部分的`制作部门`列，点击铅笔图标，即可在弹出的界面中选择制作外包公司将任务分配给对应供应商
    > 如果分配供应商界面中找不到目标供应商，请先确认该公司是否被添加到该项目外包中

    ![](../images/quick_start/producer/task_assign_out.png ':size=900')

## 审批人员设置
制作人员发布审核之后，需要主管或制片审批通过，审批之前要先设置各个环节的审核人员
1.	在项目-设置-项目环节 栏中，选择当前环节
2.	点击十图标，添加该环节的审批人员和抄送人员，审批人员一般为主管、导演和制片，抄送人员一般为制片和其他需要接收到上传消息的相关人员
3.	选择要添加的人员点击确认添加
4.	如果有多余的人员，点击头像会删除掉该人员

    ![](../images/quick_start/producer/add_supervisor.png ':size=900')

## 实体状态
+ 资产、场景、镜头类型实体的状态显示为百分数，对应为整个实体的制作上传进度，在这里可以点击将对应实体设置冻结状态  
![](../images/quick_start/producer/entity_status.png ':size=400')
  
+ 任务类型实体的状态显示为具体的信息  
![](../images/quick_start/producer/entity_status_task.png ':size=800')

## 外包文件管理
1. 点击 项目-外包 ，这里是管理该项目外包文件的地方
2. 如需为该项目新增供应商，可以点击`新增供应商`，弹出的界面内是数据库目前已记录的所有供应商 ，如果列表内没有所需供应商，需要联系技术人员配置添加
3. 左面列表内为目前项目内添加的供应商，选择要找的目标供应商
4. 选择提取任务管理，这里可以查看内部提取出的给到外包的任务文件情况
5. 点击分析更新可以分析当前任务文件版本是否为最新版本，如果不是最新版本会显示红色需更新，在对应任务条上右键可以选择提取最新文件至本地或云端
6. 点击检索可以筛选实体类型及项目环节等
7. 在制作任务管理中可以查看相关制作任务，在这里会过滤其他的任务，方便快速找到所有该外包相关任务进行后续操作
![](../images/quick_start/producer/outsource_manage.png ':size=800')