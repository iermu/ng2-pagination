# ng2-pagination

说明：

1、基于angular2的分页组件。
2、样式文件为less，改成css也很容易。

使用：

ts:
    import { PaginationComponent } from "pagination.component";

    /* add declarations for your module or declarations and exports in your shared module */

html:


    <ng-pagination [totalCount]="totalCount" [(ngModel)]="currentPage" [pageSize]="pageSize" (onPageIndexChanged)="onPageIndexChanged($event)" [currentPageIndex]="currentPageIndex"></ng-pagination>
