```mermaid
flowchart LR
    A[用户填表单] --> B[前端提交]
    B -->|POST| C[后端(Flask)] 
    C --> D[SQL 操作 DB]
    D --> E[返回结果] 
    E --> F[前端渲染展示]
```