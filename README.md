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
     -d $'{"url": "https://aweme.snssdk.com/aweme/v1/feed/?type=0&max_cursor=0&min_cursor=-1&count=6&volume=0.3333333333333333&pull_type=2&need_relieve_aweme=0&filter_warn=0&req_from&is_cold_start=0&js_sdk_version=1.2.2&app_type=normal&manifest_version_code=321&_rticket=1541682949911&ac=wifi&device_id=59121099964&iid=50416179430&os_version=8.1.0&channel=gray_3306&version_code=330&device_type=ONEPLUS%20A5000&language=zh&vid=C2DD3A72-18E8-490e-B58A-86AD20BB8035&resolution=1080*1920&openudid=27b34f50ff0ba8e26c5747b59bd6d160fbdff384&update_version_code=3216&app_name=aweme&version_name=3.3.0&os_api=27&device_brand=OnePlus&ssmix=a&device_platform=android&dpi=420&aid=1128"}'
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


