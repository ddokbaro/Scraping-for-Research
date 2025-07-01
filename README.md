# Scraping-for-Research

## 1. 소개 (Introduction)

디지털 인문학 연구를 위한 웹 스크레이핑/크롤링 파이썬 스크립트 모음입니다. 이 저장소는 다양한 웹사이트에서 데이터를 수집하고 정제하여 연구에 활용할 수 있도록 돕는 것을 목표로 합니다.

각 스크립트는 Google Colab 환경에 최적화된 노트북(`.ipynb`) 파일로 제공되어, 별도의 설치 과정 없이 누구나 쉽게 웹 브라우저에서 코드를 실행하고 데이터를 수집할 수 있습니다.

## 2. 사용 방법 (How to Use)

사용하고 싶은 스크래퍼 옆에 있는 **'Open in Colab'** 배지를 클릭하면, Google Colab에서 해당 노트북이 바로 열립니다.

노트북이 열리면, 코드 셀을 위에서부터 순서대로 실행하기만 하면 됩니다. 각 셀에는 코드에 대한 설명과 사용법이 자세히 안내되어 있습니다.

## 3. 스크래퍼 목록 (List of Scrapers)

| 스크래퍼 (Scraper) | 설명 (Description) | 바로 실행 (Launch) |
| :--- | :--- | :--- |
| **왓챠피디아 코멘트 수집**<br/>(`스크래핑_왓챠피디아_코맨트수집.ipynb`) | 왓챠피디아의 영화, TV 프로그램 등 특정 콘텐츠 페이지에 달린 모든 코멘트(ID, 별점, 내용, 좋아요, 댓글 수)를 수집합니다. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ddokbaro/Scraping-for-Research/blob/main/스크래핑_왓챠피디아_코맨트수집.ipynb) |
| *(이곳에 새로운 스크래퍼를 추가할 수 있습니다.)* | | |

## 4. 로컬 환경에서 실행하기 (For Local Environment)

만약 로컬 컴퓨터에서 이 스크립트들을 실행하고 싶다면, 아래의 과정을 따라주세요.

1. **저장소 복제(Clone)**:
   ```bash
   git clone [https://github.com/ddokbaro/Scraping-for-Research.git](https://github.com/ddokbaro/Scraping-for-Research.git)
   cd Scraping-for-Research
   ```

2. **필요 라이브러리 설치**:
   ```bash
   pip install -r requirements.txt
   ```
   > **Note**: `requirements.txt` 파일에는 `jupyter`, `selenium`, `beautifulsoup4`, `webdriver-manager` 등의 라이브러리가 포함되어야 합니다.

3. **Jupyter Notebook 실행**:
   ```bash
   jupyter notebook
   ```

## 5. 주의사항 (Disclaimer)

본 저장소의 스크립트는 교육 및 연구 목적으로 제작되었습니다. 모든 스크래핑 활동은 대상 웹사이트의 **서비스 이용 약관(Terms of Service)**을 반드시 준수해야 하며, 과도한 요청으로 서버에 부담을 주는 행위는 삼가야 합니다.

**이 코드를 사용함으로써 발생하는 모든 법적, 윤리적 책임은 전적으로 사용자 본인에게 있습니다.**

## 6. 라이선스 (License)

This project is licensed under the MIT License.
