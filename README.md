# financial_software_project
2020년도 2학기 금융소프트웨어 1팀 프로젝트입니다

https://github.com/kairess/stock_crypto_price_prediction
위 github에서 stock_samsung.ipynb를 참조하였습니다.  
참조한 부분은 소스코드의 model.py의 make_model함수입니다.  

# 크롬 웹드라이버
 87.0.4280.88 버전의 웹드라이버를 사용하였습니다.  
 크롬 버전이 다른 경우 크롬 버전에 맞는 웹드라이버를 설치하여 fe_sw_pr 디렉토리의 chromedriver.exe의 파일을 교체해주세요.  
 
# Dependencies
python 3.7  
numpy 1.18.5  
pandas 1.1.4  
matplotlib 3.3.2  
tensorflwow-cpu 2.3.1  
pymysql 0.10.1  
selenium 3.141.0  

# MySql Workbench를 통해 데이터베이스가 생성이 되어있어야 합니다.
MySql 8.0버전을 사용하였으며, username은 root로, password는 root, DB는 main_db라는 명으로 생성해주셔야합니다.  
그리고 2개의 테이블("order", "user")을 생성해야합니다.  
해당 테이블을 생성하는 DDL은 order_table_ddl.txt, user_table_ddl.txt를 확인해주시기 바랍니다.  
