---
title: Slide 模板
separator: <!--s-->
verticalSeparator: <!--v-->
theme: simple
highlightTheme: github
css: custom.css
revealOptions:
    transition: 'slide'
    transitionSpeed: fast
    center: false
    slideNumber: "c/t"
    width: 1000
---

<section data-background="./background.png">
  <div class="middle center">
    <div style="width: 100%">
      <h1>我是标题</h1>
      <hr/>
      <p></p>
      <div style="display: flex; align-items: center; justify-content: center; flex-direction: column;">
        <span style="display: flex; align-items: center; margin-bottom: 10px;">
          <p style="margin: 0; font-size: 18px; line-height: 40px;"><a href="https://github.com/zeta186012" target="_blank">这里是作者的Github</a></p>
        </span>
      </div>
      <div style="display: flex; justify-content: center; align-items: center; gap: 100px;">
        <img src="./imgs/HFUTlogo1.png" style="margin-top: 20px; height: 150px;"/>
        <img src="./imgs/CSlogo.png" style="margin-top: 20px; height: 150px;"/>
      </div>
      <p>2025.1.1</p>
    </div>
  </div>
</section> 


<!--s-->
<!-- .slide: data-background="./background.png" -->

<div class="middle center">
<div style="width: 100%">

# Part.1 大标题

一些 markdown

</div>
</div>


<!--v-->
<!-- .slide: data-background="./background.png" -->

## 标题

> test

<hr/>

```rust [1|2-3]
fn main() {
    println!("Hello World!")
}
```

...

- list 1
- list 2
    - list 2.1

1. 有序

<!--v-->
<!-- .slide: data-background="./background.png" -->


## 标题

<div class="three-line">

|表头 a|表头 b|表头 c|
|:--:|:--:|:--:|
|这是一个|一些内容|...|
|三线表|...|...|

</div>

|表头 a|表头 b|表头 c|
|:--:|:--:|:--:|
|这是一个|一些内容|...|
|普通表格|...|...|

<!--s-->

<div class="middle center">
<div style="width: 100%">

# Part.2 布局

</div>
</div>

<!--v-->
<!-- .slide: data-background="./background.png" -->


## 多列布局

<div class="mul-cols">
<div class="col">

第一列

- list
- list

</div>
<div class="col">

第二列

```python
class MyClass:
    def __init__(self, ...):
        ...
    def method(self, ...):
        ...
```

</div>
</div>

<div class="mul-cols">
<div class="col">

第一列

- list
- list

</div>
<div class="col">

第二列

1. list 
2. list 
    - list

</div>
<div class="col">

第三列

```python
class MyClass:
    def __init__(self, ...):
        ...
    def method(self, ...):
        ...
```

</div>
</div>