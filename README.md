# gg_statistics_ex
통계 기본 실습

# git repository 만들기
- repository clone
```
git clone 깃주소 statistics_ex
```

# 가상환경 구성하기
- 디렉토리 이동
```
cd statistic_ex
```
- uv 가상환경 만들기
```
uv init --bare
```

# jupyter notebook 사용환경 구성하기
- ipykernel 설치
```
uv add ipykernel
```
- 가상환경 .venv를 eda_env 이름으로 jupyter notebook에 kernel에 등록하기
```
python -m ipykernel install --user --name .venv --display-name eda_env
```

# 설치 라이브러리
```
uv add numpy
```