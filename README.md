# Crypto Trading Analyzer

비트코인 시장 분석 및 투자 추천 도구입니다. 이 도구는 다양한 기술적 지표와 시장 상황을 분석하여 투자 결정을 돕습니다.

## 주요 기능

- 실시간 비트코인 가격 데이터 분석
- 기술적 지표 계산 (20일/50일 이동평균선)
- 거래량 분석
- 변동성 분석
- 투자 추천 (매수/매도/홀딩)

## 설치 방법

1. 리포지토리 클론:
```bash
git clone https://github.com/ksj3421/crypto-trading-analyzer.git
cd crypto-trading-analyzer
```

2. 필요한 패키지 설치:
```bash
pip install -r requirements.txt
```

## 사용 방법

```bash
python crypto_analyzer.py
```

## 분석 지표

1. 기술적 분석
   - 20일/50일 이동평균선 교차
   - 현재 가격과 이동평균선 비교

2. 거래량 분석
   - 거래량/시가총액 비율 분석

3. 변동성 분석
   - 일일 변동성 계산
   - 리스크 수준 평가

4. 가격 변동 분석
   - 24시간 가격 변화율 분석
   - 과매수/과매도 상황 판단

## API 사용

- CoinGecko API를 사용하여 실시간 시장 데이터 수집
- 히스토리컬 데이터 분석을 통한 추세 파악

## 주의사항

이 도구는 참고용으로만 사용하시기 바랍니다. 실제 투자 결정은 더 많은 요소를 고려하여 신중하게 이루어져야 합니다.

## License

MIT License