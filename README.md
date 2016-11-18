# angular-2-tree-view
Angular 2 nested array tree view


Usage

Include it in app.module.ts:
```
import { TreeComponent } from './utils/tree/tree.component';
import { TreePipe } from './utils/tree/tree.pipe';
```
<br />
<br />
```
@NgModule({
  declarations: [
    ...
    TreeComponent,
    TreePipe
  ],
  ...
})
```

In your component template add:<br/>
```<app-tree [items]="array_of_items"></app-tree>```

:-)
