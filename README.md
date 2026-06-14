# SNN-DNN Nsight-Systems Profiling 


## 환경 세팅 (Prerequisites)
- **OS:** Ubuntu (WSL2 `5.15.167.4-microsoft-standard` 테스트 완료)
- **Python:** `3.12.3`
- **Nsight-Sytems:** `2024.5.1.113-245134619542v0`

### 1. 파이썬 가상환경 및 패키지 설치
```bash
python3 -m venv venv
source venv/bin/activate

# 요구 패키지 설치
pip install -r requirements.txt
```

## 실행 가이드 (Quick Start)
### 단계 1: 쉘 스크립트 실행

```bash
chmod +x src/run.sh
./src/run.sh
```

### 단계 2: 결과확인
텍스트 형식의 결과 요약을 확인과, nsys-rep 파일을 gui를 통해 상세 분석이 모두 가능합니다.

```bash
ls result
cat result/summary.txt
```

#### 실행 요약 결과 예시
<img width="1109" height="377" alt="image" src="https://github.com/user-attachments/assets/dcae6a2b-60e9-488e-a7e2-56b3e54a417e" />
