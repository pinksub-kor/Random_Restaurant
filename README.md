# Random_Restaurant
Started from difficulty choosing what to eat...
점심에 무엇을 먹을지에 대한 고민으로 시작하게 된...

Goal. Randomly choose a restaurant with given filter based on location and radius. 
목표. 주어진 좌표와 반경 내에서 주어진 필터값을 적용하여 무작위로 식당 하나를 반환하는 것. 

Direction 1. Pulling up a list of restaurants for a specific coordinates from Kakao Map API
지향점 1. 카카오 맵 API를 이용해서 고정된 좌표값을 중심으로 정해진 반경 내에 있는 식당의 목록을 출력함. 

Direction 2. Index the list, choose a random number and return the restaurant info of the number
지향점 2. 반환된 목록에 대해 인덱스를 적용하고, 인덱스의 범위 내에서 난수를 추출하여 해당하는 식당 정보를 출력. 

Direction 3. Provide a walking direction from current location to this restaurant. 
지향점 3. 무작위로 정해진 식당에 대해서 '걸어서 갈 수 있는' 경로를 출력함. 


====================================
<Considered Improvement>
1. Diverse filters(like korean, japanese, chinese, burgers and etc)
더 다양한 필터를 적용하기. 한식, 중식, 일식, 햄버거처럼. 
2. Provide alternate map API(Naver, Google, Apple, etc)
카카오맵 말고 다른 지도앱에서도 적용할 수 있도록
3. Data loading issues(How to reduce the loading time if there are large list of restaurants)
주어진 범위 내에서 많은 식당이 출력될 경우 발생하는 성능저하 문제를 어떤 식으로 해결할지. 
4. Migrating to Android, iOS app store.
현재는 웹 베이스이지만, 모바일 앱을 개발하기.
5. Possible advertisement?
광고를 받을것인가? 받는다면 어떤 광고를 받을 것인가. 
