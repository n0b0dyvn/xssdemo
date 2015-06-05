# README

[TOC]

## Cấu trúc thư mục

Thư mục     | Description
--------    | ---
css         | Chứa css của toàn bộ project. Chứa 3 file css của [**foundation**][foundation]. Ko cần đụng tới
img         | Chứa hình ảnh của toàn bộ project, bao gồm img,icon
js          | chứa các file js của [**foundation**][foundation]. Không cần đụng tới
module      | chứa các Thư Mục module của extension.
__background | Chứa file background.js. Xem thêm [**Background**][1].
__browseraction | Chứa file browseraction.js/popup.[html/js]. Xem thêm [**Browser Action**][2]
__pageaction | Chứa file pageaction.[html/js]. Xem thêm [**Page Action**][3]
__panel | Chứa file panel.[html/js]. Xem thêm [**Panel**][3]
manifest.json          | là metadata của extension. Xem thêm tại [**Manifest**][5]

## Background

![]( https://developer.chrome.com/static/images/overview/arch-1.gif)

Nút màu xanh là **Page Action**. Nút màu vàng là **Browser Action**. Cả 2 nút đều được điều khiển hành vi bởi 1 trang gọi là **background**. Có 2 loại **background** là **persistent**(mãi mãi) và **non-persistent**(Event Page)

> Event Page: Chúng ta sẽ tập trung vào Event Page. Event Page là dạng background chỉ chạy khi có event xảy ra. 

## Browser Action

## Page Action

## Panel

[1]:#background
[2]:#browseraction
[3]:#pageaction
[4]:#panel
[5]:https://developer.chrome.com/extensions/manifest
[foundation]:http://foundation.zurb.com/docs/

