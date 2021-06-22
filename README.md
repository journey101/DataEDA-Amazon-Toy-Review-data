# DataEDA-Amazon-Toy-Review-data

## 프로젝트 소개: 
본 프로젝트는 '아마존 장난감 데이터'를 분석하여 기본적인 데이터 EDA를 연습하기 위한 의도로 시작되었습니다.
잠재 고객을 '조카'로 가정하여, 어린이 고객에게 어떤 선물을 추천하면 좋을지 'A안/B안'으로 결론을 내는 과정을, 
데이터 분석을 통해 찾아보는 컨셉으로 스토리텔링하였습니다. 

## 가설 소개: 
Q. 조카 선물로 어떤 장난감을 선물해줘야 잘 주는 걸까? (아마존에서 구입하는 상황)
- 가설1) 가장 판매량이 높은 10개의 브랜드 중에서 고르면 될까?
- 가설2) 그 다음엔 가격이 비싼 것을 사야 할 지? (비싸면 장땡일까?)
- 가설3) 리뷰 평점이 높은 것을 사야 할지?
- 가설4) 리뷰의 양이 많은 것을 사야 할지?
 => 위 가설에서 찾은 필터를 종합하여 선물 A안, B안 고르기!

## 데이터 소개: 

캐글에 있는 '아마존 장난감 데이터('Toy Products on Amazon, 10,000 toy products on Amazon.com')를 사용하였습니다. 

※[데이터 출처](https://www.kaggle.com/PromptCloudHQ/toy-products-on-amazon)

<주요 특성(feature)설명>
- product_name
- manufacturer (The item manufacturer, as reported on Amazon. Some common "manufacturers", like Disney, actually outsource their assembly line.)
- price
- number_available_in_stock
- number_of_reviews
- number_of_answered_questions (Amazon includes a Question and Answer service on all or most of its products. This field is a count of how many questions that were asked actually got answered.)
- average_review_rating
- customer_reviews (A string entry with all of the product's JSON reviews.)
