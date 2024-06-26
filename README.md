# CPR Service
한국산업단지공단 내 ESG 경영 시급 기업 추천서비스: 위기에 빠진 중소기업을 구하는 CPR 서비스
> 
> 수행 기관: 한국산업단지공단
> 
> 프로젝트 기간: 2023.9.1 ~ 2023.10.13

## 팀원 소개
- 최정인 (팀장/복단대학교 영어영문학과 졸업) : 기획 및 방향성 제시, 데이터 전처리, 태블로 시각화
- 공은지 (성신여자대학교 통계학과 졸업) : 기획 및 지표 설정, 데이터 전처리 및 모델링
- 김규리 (명지대학교 융합소프트웨어학부 3학년): 기획 및 지표설정, 크롤링 및 데이터셋 구축, 모델링
- 윤채령 (한국외국어대학교 스페인어학과 졸업): 기획, 자료 및 논문 조사, PPT
- 허진우 (한국교통대학교 컴퓨터공학과 4학년): 기획 및 지표설정, 크롤링 및 데이터셋 구축, 태블로 시각화

## 프로젝트 소개
- 국제적인 ESG 규제 강화에 발맞추어 한국산업단지공단은 2021년부터 ESG 경영 도입이 어려운 입주기업을 지원하고 있음.
- 이에 한국산업단지공단은 ESG 지원사업 대상 기업을 효과적으로 선정하는데 도움을 주는 서비스를 필요로 하고 있음.
- 본 프로젝트에서는 ESG 경영 지원 기준 지표 마련 및 RFM(Recency, Frequency, Monetary) 모델링을 통한 ESG 경영 지원 시급 기업 추천 서비스를 개발하고자 함.

## CPR Service 소개
> 기업의 ESG 경영 시급도를 정확하게 파악하여 위기에 빠진 중소기업을 구하는 'CPR 서비스'
- 중앙 모니터링 서비스를 뜻하는 Central Monitoring Service, 우선 지원 기업 추천 서비스를 뜻하는 Priority Recomendation Service의 앞글자를 결합하여 'CPR 서비스'라는 명칭을 창안함.
- 산업단지 입주기업의 재무정보(영업이익률, 3년 평균 매출액, 매출액 대비 연구개발비, 부채비율)와 수출 여부, 기업 규모, 특허/메인비즈/이노비즈 여부 등의 데이터를 RFM 모델 기반 시급도 측정 모델에 입력하면 기업의 ESG 경영 시급도가 도출됨
- 산업단지 및 업종별 입주기업의 ESG 경영 시급도를 추적할 수 있는 모니터링 대시보드와 지원 사업 참여기업을 관리할 수 있는 대시보드를 제공함


## 서비스 주요 기능
1. 시급기업 추천
    * ESG 경영 지원 대상 선정 기준 지표를 기반으로 ESG 시급 기업을 추천함.
2. 기업별 ESG 시급 현황 모니터링
    * 산업단지 입주 기업의 ESG 시급 현황을 모니터링 가능함.
3. 참여 기업의 변화 대시보드
    * 대시보드를 통해 ESG 지원 사업 참여기업의 변화를 시각적으로 볼 수 있음.

## 대시보드 설명
기업 내부 기밀사항으로 기업명, 기업정보 등에 해당되는 모든 정보는 블러처리함. 
| 산업단지 내 기업의 ESG 시급 현황을 추적하는 대시보드 | 대시보드 기능 설명 | 
| :----------------- | :----------------- |
| <img src="https://github.com/GyuriKim12/KICOX_ESG_Monitoring_Service/assets/80877176/cde53532-84ad-42e7-9cb4-b1c942cd120b"> | 1. 산업단지 내 모든 기업의 ESG 시급도와 정보를 간편하게 확인할 수 있음 <br> 2. 산업단지 및 업종별로 기업의 ESG 시급도 분포를 파악할 수 있음. |
| 산업단지 내 기업별 상세 정보를 확인하는 대시보드 | 대시보드 기능 설명 | 
| <img src="https://github.com/GyuriKim12/KICOX_ESG_Monitoring_Service/assets/80877176/428334ef-eff8-4e6e-ab1b-69954338703c"> | 1. 기업의 ESG 경영 시급도 및 점수를 확인할 수 있음. <br> 2. 동종 업계 내 기업의 매출액 위치를 확인할 수 있음. <br> 3. 기업의 기본 정보 및 재무 정보를 확인할 수 있음. <br> 4. 시급도에 긍정적인 영향을 주는 요소와 부정적인 영향을 주는 요소를 확인할 수 있음.|
| ESG 지원 사업 참여기업의 현황 파악 대시보드 | 대시보드 기능 설명 | 
|<img src="https://github.com/GyuriKim12/KICOX_ESG_Monitoring_Service/assets/80877176/8bc05363-0e6c-4490-a130-73558aa18bbd"> | 1. ESG 경영 지원 현황을 파악할 수 있다. <br> 2. ESG 경영 지원 사업 참가 후 기업의 변화를 확인할 수 있다.|

## 모델링 코드 확인 및 실행
```
git clone https://github.com/GyuriKim12/KICOX_ESG_Monitoring_Service.git
cd KICOX_ESG_Monitoring_Service/cd code
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
