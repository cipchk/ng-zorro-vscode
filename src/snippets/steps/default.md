---
description:
  zh-CN: "步骤条"
  en-US: "Steps"
---

```html
<nz-steps [(nzCurrent)]="${1:current}"${2: [nzStatus]="'${3|wait,process,finish,error|}'"}${4: nzSize="small"}${5: nzDirection="${6|horizontal,vertical|}"}${7: nzProgressDot}>
  <nz-step [nzTitle]="'${8}'" [nzDescription]="'${9}'"></nz-step>
  $0
</nz-steps>
<div class="steps-content">

</div>
```
