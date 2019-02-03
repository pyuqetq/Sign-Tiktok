[Switch to Douyin(Chinese version)](https://github.com/JokeAI/Sign-DouYin)

## Prior Declaration

+ This demo if for data analysis purposes only, not available for any other purpose
+ If the project infringes on your company's rights, I will delete it immediately.
+ Demos can only be requested for limited times.  
+ Any questions, pls email jokeai@yandex.com

## Gen as/cp/mas parameters
```
curl -X "POST" "http://jokeai.zongcaihao.com/tiktok/v872/sign" \
     -H 'Content-Type: application/json' \
     -d $'{"url": "https://api.tiktokv.com/aweme/v1/feed/?retry_type=no_retry&app_language=zh-Hant&language=zh&region=TW&sys_region=CN&carrier_region=HK&carrier_region_v2=454&build_number=9.2.0&timezone_offset=28800&timezone_name=Asia%2FShanghai&mcc_mnc=46000&is_my_cn=1&fp=PrT_c2LZLMwbFlqMFlU1LSFIJzQZ&account_region=HK&pass-region=1&pass-route=1&iid=6652982632757020421&device_id=6597408310473934338&ac=wifi&channel=googleplay&aid=1233&app_name=musical_ly&version_code=920&version_name=9.2.0&device_platform=android&ab_version=9.2.0&ssmix=a&device_type=ONEPLUS+A5000&device_brand=OnePlus&os_api=27&os_version=8.1.0&openudid=4617150637217100&manifest_version_code=2018111637&resolution=1080*1920&dpi=420&update_version_code=2018111637&_rticket=1543507053287&count=6&type=0&max_cursor=0&min_cursor=-1&pull_type=2"}'
```

## Gen device info(install_id,device_id)
[https://jokeai.zongcaihao.com/tiktok/v872/device](https://jokeai.zongcaihao.com/tiktok/v872/device)

#### 3. API：

New algorithm can be used with more new APIs... 

| | New v2 as/mas   | 
| ------------- | ------------- | 
| Home feeds  | [/feed](https://jokeai.zongcaihao.com/tiktok/v872/feed)  | 
| User's videos  | [/aweme/post](https://jokeai.zongcaihao.com/tiktok/v872/aweme/post?user_id=6603395355915993094&max_cursor=0&count=20) 
| User's favirite videos | [/aweme/favorite](https://jokeai.zongcaihao.com/tiktok/v872/aweme/favorite?user_id=6603395355915993094&max_cursor=0&count=20) 
| Personal profile  | [/user](https://jokeai.zongcaihao.com/tiktok/v872/user?user_id=6603395355915993094)  |
| User's followings  | [/user/following/list](https://jokeai.zongcaihao.com/tiktok/v872/user/following/list?user_id=6603395355915993094)  |
| User's followers  | [/user/follower/list](https://jokeai.zongcaihao.com/tiktok/v872/user/follower/list?user_id=6603395355915993094)  | 
| Videos's comments  | [/comment/list](https://jokeai.zongcaihao.com/tiktok/v872/comment/list?aweme_id=6626744652743576838&cursor=0)  | 
| Hot Topics | [/category/list](https://jokeai.zongcaihao.com/tiktok/v872/category/list?cursor=0)  | 
| Topic related videos| [v2/challenge/aweme](https://jokeai.zongcaihao.com/tiktok/v872/challenge/aweme?ch_id=20262712&cursor=0)  | 
| Topic detail info| [v2/challenge/detail](https://jokeai.zongcaihao.com/tiktok/v872/challenge/detail?ch_id=20262712)  | 
| Search users| [v2/search/discover](https://jokeai.zongcaihao.com/tiktok/v872/search/discover?keyword=lucas&cursor=0)  |  
| Search music| [v2/search/music](https://jokeai.zongcaihao.com/tiktok/v872/search/music?keyword=lucas&cursor=0)  | 
| Search topic| [v2/search/challenge](https://jokeai.zongcaihao.com/tiktok/v872/search/challenge?keyword=lucas&cursor=0)  |  


