# News_RSS_Feed_Download
http://egloos.zum.com/wyb330/v/4202899를 참조

라이브러리:feedparser, pymysql, beautifulsoup3, urllib2 ,time, konlpy

Crawler.py  - Rss_feed의 item 주소를 크롤링하여 형태소 분석
DataBase.py   - MySQL
LogFile.py  - Log파일 저장
RSSRobot.py - RSS_feed 로봇
rss_feedlst - RSS주소 목록 저장

RSSRobot.py(main)
rss_feed.lst의 주소를 읽어와 각각의 item들에 대하여 사전을 만들고 이를 저장

TODO
- 예외처리부분에서 에러 발생(수정요망)
