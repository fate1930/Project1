# Project1设计文档 张璐 19302010023

## 地址

仓库地址：https://github.com/fate1930/Project1.git

页面地址：https://fate1930.github.io/Project1/
## 主要界面

### index.html

用于登录以及指向注册界面，比例随页面变化，登录后跳转至home.html，全部完成条目。

### register.html

用于进行注册，比例随页面变化，注册后跳转至index.html，全部完成条目。

### home.html

用于跳转其他界面，比例随页面变化，展示图片，所展示的六张图片使用grid进行布局，一行所展示图片随着页面宽度变化。使用object-fit：cover的方式，随页面变化对图片进行自动裁剪，全部完成条目。

### browser.html

用于分条目对图片进行搜索，比例随页面变化，图片同样使用grid进行布局，使用object-fit：cover的方式，随页面变化对图片进行自动裁剪，全部完成条目。

### search.html

对标题或者描述对照片进行搜索，比例随页面变化，图片随页面等比变化，全部完成条目。

### details.html

对图片进行详细描述，由其它图片跳转而来，比例随页面变化，全部完成条目。

### upload.html

对图片信息进行上传，使用一个div和label分别对上传图片的名字进行显示，以及代替上传按钮。比例随页面变化，上传后跳转至mypicture.html，全部完成条目。

### mypicture.html

对已有图片进行删除以及修改，经过Modify按钮可跳转至upload.html修改图片信息，比例随页面变化，全部完成条目。

### mycollection.html

对收藏图片进行删除，比例随页面变化，全部完成条目。

## Bonus完成情况

### 更复杂的图片处理

大部分页面对图片使用放缩的方法进行修改，home.html以及browser.html两个页面对图片固定在一个div之中并且固定div的长宽，在使用object-fit：cover的css属性对图片进行自动裁剪，使得图片可以随着页面的变化自动进行裁剪。

### 响应式布局

对大部分页面的元素使用百分比以及vmax的单位，使得页面可以随着网页大小的变化进行等比例放缩。在home.html以及browser.html两个页面中，对包含图片的div使用grid进行布局，使得grid块可以根据页面大小的变化自动排列图片的大小以及占位情况。

## 意见与建议

暂时木有啥么建议
