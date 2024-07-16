---
title: People
date: 2022-10-24

type: landing

# sections:
#   - block: markdown
#     content:
#       title:  
#       subtitle: ''
#       text: |

#         ## Faculty
#         - [王鹃](https://cse.whu.edu.cn/info/1255/3270.htm)
#         - **张三** - 实验室主任  
#         [张三的主页](https://example.com/zhangsan)  
#         职责：负责实验室整体研究方向和项目管理。

#         ## 博士
#         - 赵六
#         - [钱七](https://example.com/qianqi)

#         ## 硕士
#         - 孙八
#         - [周九](https://example.com/zhoujiu)

#         ## 本科生
#         - 吴十
#         - [郑十一](https://example.com/zhengshiyi)

#         ## 毕业生
#         - [王十二](https://example.com/wangshier)
#         - 陈十三



sections:
  - block: people
    content:
      # title: Our Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
          - Faculty
          - Ph.D. Students
          - Master Students
          - Undergraduate students
          - Graduates
      sort_by: Params.ID
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
---