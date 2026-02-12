# Belina

## 변경사항 반영 방법 (GitHub + Render)

`index.html`을 수정한 뒤 아래 3단계만 하면 됩니다.

### 1) 변경 파일 스테이징 (add)
```powershell
git add index.html
```

파일 전체 변경을 한 번에 올리고 싶으면:
```powershell
git add .
```

### 2) 커밋 (commit)
```powershell
git commit -m "Update index.html"
```

메시지는 작업 내용에 맞게 바꿔도 됩니다.

### 3) 원격 저장소로 업로드 (push)
```powershell
git push
```

푸시가 끝나면 Render가 자동 배포를 시작합니다.

## 상태 확인 명령어

현재 변경 상태 확인:
```powershell
git status --short
```

최근 커밋 확인:
```powershell
git log --oneline -n 3
```

## 자주 쓰는 전체 흐름
```powershell
cd C:\Users\박지민\Desktop\Belina
git add index.html
git commit -m "작업 내용 요약"
git push
```
