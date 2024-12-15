# 의약품 안전나라 크롤링

### - '의약품안전나라'에서 크롤링 진행 
### - 총 37050개의 데이터가 담긴 csv파일과 이미지 파일을 생성했으나 용량문제로 csv와 이미지는 업로드 불가

 1)의약품안전나라.py에서 페이지 번호와 csv파일명을 잘 바꿔가며 csv생성
 
 2)확인.py 를 통해 생성된 csv파일이 잘생성되었는지 html로 확인 (생략가능)
 
 3)DB.py 를 통해 MySQL 워크벤치에 업로드 : 마찬가지로 csv파일명과 DB 비밀번호는 본인 DB에 맞게 변경후 실행해야함