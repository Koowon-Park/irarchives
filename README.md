(한글 번역본)
# irarchives
==========

요약
----
Reddit용 NSFW 역이미지 검색

구현
----
http://i.rarchives.com (경고: **NSFW**)

개요
----
많은 NSFW Reddit 게시글에는 이미지에 대한 추가 정보가 포함되어 있습니다.

이 저장소에는 다음이 포함되어 있습니다:
* Reddit 게시글에서 이미지를 수집하여 데이터베이스에 저장하는 스크립트
* 데이터베이스를 검색할 수 있는 웹 인터페이스

요구 사항
--------
Python 2.6.x에서 테스트되었습니다. 2.7 및 아마도 2.5에서도 작동할 수 있습니다(2.4에서는 JSON 제한으로 인해 호환되지 않습니다).

이미지 계산에는 Python Imaging Library, 또는 [PIL](http://www.pythonware.com/products/pil/)이 필요합니다.

참고
----
명백한 이유로 저장소에는 데이터베이스가 포함되어 있지 않습니다.

데이터베이스는 사용자가 직접 생성해야 하며, 요청하면 현재 150만 개 이상의 해시된 이미지가 저장된 데이터베이스 사본을 받을 수도 있습니다.


irarchives
==========

Summary
-------
NSFW reverse image search for reddit

Implementation
--------------
http://i.rarchives.com (Warning: **NSFW**)

Overview
--------
Many NSFW reddit posts contain more information about an image. 

The repo contains:
* a script to scrape images from reddit posts and store the data in a database.
* a web interface for searching the database

Requirements
------------
Tested with Python 2.6.x. Should work with 2.7 and possibly 2.5 (not compatible with 2.4 due to JSON limitations).

The image calculations require Python Imaging Library, or [PIL](http://www.pythonware.com/products/pil/).

Notes
-----
There is no database included with the repo for obvious reasons. 

The database will have to be generated by the user or, if you ask nicely, you can have a copy of the current database which has over 1.5 million hashed images.
