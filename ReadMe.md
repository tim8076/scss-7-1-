## 本專案為 scss 7 + 1 結構

[7 + 1 參考資料](https://openclassrooms.com/en/courses/5625786-produce-maintainable-css-with-sass/5723581-use-the-7-1-pattern-for-a-manageable-codebase)

資料夾結構如下:

專案共用變數，mixin等
@import 'abstract/variables';
@import 'abstract/mixins';

專案 基礎樣式
@import 'base/reset';
@import 'base/base';

專案layout元件
@import 'layout/grid';
@import 'layout/header';
@import 'layout/footer';

專案個別頁面樣式
@import 'page/index';

元件樣式
@import 'components/buttons';

helpers 樣式
@import 'helpers/helpers';




