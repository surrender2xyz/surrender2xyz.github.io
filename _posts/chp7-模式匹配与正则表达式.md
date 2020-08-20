---
layout:     post
title:      Hello, 2020, THIS IS MY FIRST BLOG!
subtitle:    "\"Hello World, Hello Blog\""
date:       2020-04-04
author:     surrender
categories: true
tags:
    - python
---

# 1 习题

1．创建 Regex 对象的函数是什么？
2．在创建 Regex 对象时，为什么常用原始字符串？
3．search()方法返回什么？
4．通过 Match 对象，如何得到匹配该模式的实际字符串？
5．用 r'(\d\d\d)-(\d\d\d-\d\d\d\d)'创建的正则表达式中，分组 0 表示什么？分组 1
呢？分组 2 呢？
6．括号和句点在正则表达式语法中有特殊的含义。如何指定正则表达式匹配真正的括号和句点字符？
7．findall()方法返回一个字符串的列表，或字符串元组的列表。是什么决定它提供哪种返回？
8．在正则表达式中，|字符表示什么意思？
9．在正则表达式中，?字符有哪两种含义？
10．在正则表达式中，+和*字符之间的区别是什么？
11．在正则表达式中，{3}和{3,5}之间的区别是什么？
12．在正则表达式中，\d、\w 和\s 缩写字符类是什么意思？
13．在正则表达式中，\D、\W 和\S 缩写字符类是什么意思？
14．如何让正则表达式不区分大小写？
15．字符.通常匹配什么？如果 re.DOTALL 作为第二个参数传递给 re.compile()，它会匹配什么？
16．.*和*?之间的区别是什么？
17．匹配所有数字和小写字母的字符分类语法是什么？
18．如果 numRegex = re.compile(r'\d+')，那么 numRegex.sub('X', '12 drummers, 11
pipers, five rings, 3 hens')返回什么？
19．将 re.VERBOSE 作为第二个参数传递给 re.compile()，让你能做什么？
20．如何写一个正则表达式，匹配每 3 位就有一个逗号的数字？它必须匹配以下数字：
 '42'
 '1,234'
 '6,368,745'
但不会匹配：
 '12,34,567' （逗号之间只有两位数字）
 '1234' （缺少逗号）
21．如何写一个正则表达式，匹配姓 Nakamoto 的完整姓名？你可以假定名字总是出现在姓前面，是一个大写字母开头的单词。该正则表达式必须匹配：
 'Satoshi Nakamoto'
 'Alice Nakamoto'
 'RoboCop Nakamoto'
但不匹配：
 'satoshi Nakamoto'（名字没有大写首字母）
 'Mr. Nakamoto'（前面的单词包含非字母字符）
 'Nakamoto' （没有名字）
'Satoshi nakamoto'（姓没有首字母大写）
22．如何编写一个正则表达式匹配一个句子，它的第一个词是 Alice、Bob 或Carol，第二个词是 eats、pets 或 throws，第三个词是 apples、cats 或 baseballs。该句子以句点结束。这个正则表达式应该不区分大小写。它必须匹配：
 'Alice eats apples.'
 'Bob pets cats.'
 'Carol throws baseballs.'
 'Alice throws Apples.'
 'BOB EATS CATS.'
但不匹配：
 'RoboCop eats apples.'
 'ALICE THROWS FOOTBALLS.'
 'Carol eats 7 cats.'

# 2 实践

