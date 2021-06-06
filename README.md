## 简介

#### 这是什么

这是fork自[fengyuanchen/viewerjs](https://github.com/fengyuanchen/viewerjs)的仓库，从[V.1.9.2](https://github.com/fengyuanchen/viewerjs/commit/84f87cc041261436ff28505403a6825efc48e85d)开始。



#### 它与[fengyuanchen/viewerjs](https://github.com/fengyuanchen/viewerjs)有什么不同之处

对于[fengyuanchen/viewerjs](https://github.com/fengyuanchen/viewerjs)做出了以下修改：



##### 20210606

---

- `README.md`

	> 为了显示本笔记，将其重命名为`README.src.md`

- `src/js/methods.js`

	- `toggle()`

		> 当图片不等于初始尺寸时，执行`toggle()`会恢复为默认尺寸

- `src/js/handlers.js`

	- `dblclick()`

		> 当图片处于缩放状态时，双击会把图片移动到中心位置
	
- `src/css/viewer.css` & `src/css/viewer.scss`

	```css
	.viewer-backdrop {
	  background-color: rgba(0, 0, 0, 0.7); /* 透明度改为0.7，使遮罩颜色更浓 */
	}
	```