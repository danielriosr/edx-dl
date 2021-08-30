# edx-dl

## 0. Motivation

I was using `https://github.com/antinucleon/edx-dl` to backup some courses I wanted to learn. However, it seems that the original author no longer can maintain it. So I updated some lines to have it properly working, and will try to keep it up to date.

## 1. Usage
- Download `chromedriver` and put it into `./bin`
- Install aria2
- Run `pip install -r requirements.txt`
- Run `edx-dl.py`, input user name, password, and course url (eg: `https://learning.edx.org/course/course-v1:CaltechX+BEM1105x+3T2020/home`)
- Wait for a while

## 2. Remark
- Headless mode may be buggy due to lacking wait for some loadings. However I am lazy to make it correct. 
