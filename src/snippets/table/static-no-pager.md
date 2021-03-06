## zh-CN

不分页静态数据

```html
<nz-table [nzData]="${1|list,data|}" [nzShowPagination]="false">
  <thead>
    <tr>
      <th>$0</th>
      <th nzWidth="300px"></th>
    </tr>
  </thead>
  <tbody>
    <tr *ngFor="let ${2:i} of $1">
      <td>{{${2}.title}}</td>
      <td>
        <a (click)="next(${2})">下一级</a>
        <nz-divider nzType="vertical"></nz-divider>
        <a (click)="edit(${2})">编辑</a>
        <nz-divider nzType="vertical"></nz-divider>
        <nz-popconfirm [nzTitle]="'确定要删除吗？'" (nzOnConfirm)="del(${2})">
          <a nz-popconfirm>删除</a>
        </nz-popconfirm>
      </td>
    </tr>
  </tbody>
</nz-table>
```

## en-US

Table not pagination

```html
<nz-table [nzData]="${1|list,data|}" [nzShowPagination]="false">
  <thead>
    <tr>
      <th>$0</th>
      <th nzWidth="300px"></th>
    </tr>
  </thead>
  <tbody>
    <tr *ngFor="let ${2:i} of $1">
      <td>{{${2}.title}}</td>
      <td>
        <a (click)="next(${2})">Next</a>
        <nz-divider nzType="vertical"></nz-divider>
        <a (click)="edit(${2})">Edit</a>
        <nz-divider nzType="vertical"></nz-divider>
        <nz-popconfirm [nzTitle]="'Are you sure?'" (nzOnConfirm)="del(${2})">
          <a nz-popconfirm>Delete</a>
        </nz-popconfirm>
      </td>
    </tr>
  </tbody>
</nz-table>
```
