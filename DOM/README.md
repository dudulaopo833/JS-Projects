# Summary
### CSS ---style---> HTML <---DOM-BOM-ESCAMScript--- JS   
* DOM(Document Object Model): 首先浏览器会把html内容解析成文档对象模型，然后就可以用docment.xxx, window.xxx 去操作DOM元素   
* BOM(Broswer Object Model): 处理浏览器导航, 窗口, 分辨率, history, cookie等操作   
* ESCAMScript(JS standard): JS标准     
> DOM1(DOM Core, DOM HTML)   
> DOM2(DOM Views, DOM Events, DOM style, DOM Traversal and Range)   
> DOM3(DOM load And Save, DOM Validation)    
* DOM 支持多种文档类型(html-<!doctype html>, xml-<?xml>)
* DOM 节点类型(nodeType)常用的有八种(element-1, attribute=2, text-3, comment-8, document-9, documentType-10, documentFragment-11)
```
属性： 
DOM.nodeType, DOM.nodeName, DOM.nodeValue, DOM.attributes, DOM.childNodes, DOM.innerHTML
document.body.childNodes, document.doctype.nodeName, 
方法：
document.createDocumentFragment, document.getElementById, document.getElementsByTagName, document.createElement, 
DOM.appendChild
```