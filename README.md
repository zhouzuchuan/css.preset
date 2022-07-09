# css.preset

依据 [Emmet](https://github.com/emmetio/emmet) 的 css 规则 预设了部分常用样式，以便开发调试

## 下载

```bash

yarn add css.preset

# 或

npm install css.preset


```

## 使用

```html
<div class="fz12 lh30 mt20 fwb">css.preset</div>
```

## 属性

### 数字规则

命名规则
属性简称加上数值

| 属性           | 间隔 | 简称    |                    |
| -------------- | ---- | ----- | ----------------   |
| margin         | 4    | `ma`  | `ma-0` - `ma-20`   |
| margin-top     | 4    | `mt`  | `mt-0` - `mt-20`   |
| margin-bottom  | 4    | `mb`  | `mb-0` - `mb-20`   |
| margin-left    | 4    | `ml`  | `ml-0` - `ml-20`   |
| margin-right   | 4    | `mr`  | `mr-0` - `mr-20`   |
| padding        | 4    | `pa`  | `pa-0` - `pa-20`   |
| padding-top    | 4    | `pt`  | `pt-0` - `pt-20`   |
| padding-right  | 4    | `pr`  | `pr-0` - `pr-20`   |
| padding-bottom | 4    | `pb`  | `pb-0` - `pb-20`   |
| padding-left   | 4    | `pl`  | `pl-0` - `pl-20`   |
| line-height    | 2    | `lh`  | `lh-0` - `lh-20`   |
| font-size      | 2    | `fz`  | `fz-0` - `fz-20`   |
| font-weight    | 100  | `fw`  | `fw0` - `fw1000`   | 

### 单一规则

| 属性            | Rule            | 类名         |
| --------------- | --------------- | ------------ |
| width           | 100%            | `wp100`      |
|                 | 50%             | `wp50`       |
|                 | 33.33%          | `wp33`       |
| height          | 100%            | `hp100`      |
| position        | static          | `pss`        |
|                 | relative        | `psr`        |
|                 | absolute        | `psa`        |
|                 | fixed           | `psf`        |
| float           | none            | `fln`        |
|                 | left            | `fll` / `fl` |
|                 | right           | `flr` / `fr` |
| clear           | none            | `cln`        |
|                 | left            | `cll`        |
|                 | right           | `clr`        |
|                 | both            | `clb`        |
| display         | none            | `dn`         |
|                 | block           | `db`         |
|                 | inline-block    | `dib`        |
|                 | inline          | `di`         |
|                 | flex            | `df`         |
|                 | inline-flex     | `dif`        |
| visibility      | visible         | `vv`         |
|                 | hidden          | `vh`         |
| overflow        | hidden          | `ovh`        |
|                 | auto            | `ova`        |
|                 | scroll          | `ovs`        |
|                 | visible         | `ovv`        |
| clip            | auto            | `cpa`        |
| resize          | none            | `rzn`        |
|                 | vertical        | `rzv`        |
|                 | horizontal      | `rzh`        |
| cursor          | pointer         | `curp`       |
|                 | auto            | `cura`       |
|                 | move            | `curm`       |
| box-sizing      | content-box     | `bxzcb`      |
|                 | border-box      | `bxzbb`      |
| z-index         | 0               | `zi0`        |
|                 | -1              | `zi-1`       |
| text-decoration | underline       | `tdu`        |
|                 | line-through    | `tdl`        |
|                 | none            | `tdn`        |
| font-weight     | normal          | `fwn`        |
|                 | bold            | `fwb`        |
|                 | bolder          | `fwbr`       |
|                 | lighter         | `fwlr`       |
| font-style      | normal          | `fsn`        |
|                 | italic          | `fsi`        |
| font-variant    | normal          | `fvn`        |
|                 | small-caps      | `fvsc`       |
| vertical-align  | super           | `vasp`       |
|                 | sub             | `vasb`       |
|                 | sub             | `vat`        |
|                 | top             | `vasb`       |
|                 | bottom          | `vab`        |
|                 | middle          | `vam`        |
|                 | text-top        | `vatt`       |
|                 | text-bottom     | `vatb`       |
|                 | baseline        | `vabl`       |
| text-align      | left            | `tal`        |
|                 | right           | `tar`        |
|                 | center          | `tac`        |
|                 | justify         | `taj`        |
| text-align-last | auto            | `tala`       |
|                 | left            | `tall`       |
|                 | right           | `talr`       |
|                 | center          | `talc`       |
| text-decoration | none            | `tdn`        |
|                 | underline       | `tdu`        |
|                 | overline        | `tdo`        |
|                 | line-through    | `tdl`        |
| text-indent     | -9999px         | `ti-`        |
| text-justify    | auto            | `tja`        |
|                 | nter-word       | `tjiw`       |
|                 | inter-ideograph | `tjii`       |
| text-transform  | none            | `ttn`        |
|                 | capitalize      | `ttc`        |
|                 | uppercase       | `ttu`        |
|                 | lowercase       | `ttl`        |
| letter-spacing  | 0               | `lts`        |
|                 | -4px            | `lts-4`      |
|                 | -6px            | `lts-6`      |
| white-space     | normal          | `whsn`       |
|                 | pre             | `whsp`       |
|                 | nowrap          | `whsnw`      |
|                 | pre-wrap        | `whspw`      |
|                 | pre-line        | `whspl`      |
| word-break      | normal          | `wobn`       |
|                 | keep-all        | `wobk`       |
|                 | break-all       | `wobba`      |
| word-wrap       | normal          | `wownm`      |
|                 | none            | `wown`       |
|                 | break-word      | `wowb`       |
| background      | transparent     | `bgt`        |
| background-size | contain         | `bgszct`     |
|                 | cover           | `bgszcv`     |
| transform       | scaleY(-1)      | `flipy`      |
|                 | scaleX(-1)      | `flipx`      |
| filter          | grayscale(1)    | `grayscale`  |

### 组合规则

#### `lay-list`

inline 布局， 通过子类 `item` 来实现

```html
<div class="lay-list">
    <div class="item">1</div>
    <div class="item">2</div>
    <div class="item">3</div>
</div>
```

#### `flex-box`

flex 布局， 子类 `item`（拉伸填充剩余区域）`box-pack`（让其内部水平以及垂直居中）

```html
<div class="flex-box">
    <div class="box-pack">label</div>
    <div class="item">content</div>
    <div>tip</div>
</div>
```

`vertical` 来实现垂直布局 （父元素必须设置高度）

```html
<div style="height: 400px;">
    <div class="flex-box vertial">
        <div>header</div>
        <div class="item">content</div>
        <div>footer</div>
    </div>
</div>
```

`middle` 伸缩项水平垂直居中

```html
<div style="height: 400px;">
    <div class="flex-box middle">
        <div>left</div>
        <div class="item">centent</div>
        <div>right</div>
    </div>
</div>
```

#### `help-middle`

辅助内部元素居中

```html
<div class="help-middle">
    <div>居中元素</div>
</div>
```

#### `cf`

清楚浮动

#### `ell`

单行文字超出范围出现省略号

也可以使用

`clamp_2` 两行文字超出范围出现省略号

`clamp_3` 三行文字超出范围出现省略号

#### `eq`

高度背景对齐填充

#### `not-viewport`

将元素移除视口可见区域
