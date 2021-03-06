---
title: "Helm Env"
---

## helm env

헬름 클라이언트 환경변수 정보

### 개요


Env 는 헬름에서 사용 중인 모든 환경변수 정보를 출력한다.


```
helm env [flags]
```

### 옵션

```
  -h, --help   env 에 대한 도움말
```

### 부모 명령어에서 상속된 옵션들

```
      --add-dir-header                   이 값이 참이면, 헤더에 파일 디렉토리를 추가
      --alsologtostderr                  표준 오류를 로그 및 파일로 표시
      --debug                            장황한(verbose) 출력 활성화
      --kube-apiserver string            쿠버네티스 API 서버의 주소 및 포트
      --kube-context string              사용할 kubeconfig 컨텍스트 이름
      --kube-token string                인증에 사용될 베어러(bearer) 토큰
      --kubeconfig string                kubeconfig 파일 경로
      --log-backtrace-at traceLocation   로깅 시 N 행에 걸친 스택 추적 내용을 표시 (기본값 :0)
      --log-dir string                   값을 지정하면, 지정한 디렉토리에 로그 파일 기록
      --log-file string                  값을 지정하면, 지정한 로그 파일 사용
      --log-file-max-size uint           로그파일이 증가할 수 있는 최대 크기 지정. 단위는 메가바이트이다. 값이 0이면, 최대 파일크기는 무제한. (기본값 1800)
      --logtostderr                      로그를 파일이 아닌 표준 출력으로 표시 (기본값 true)
  -n, --namespace string                 요청에 대한 네임스페이스 지정
      --registry-config string           레지스트리 구성 파일에 대한 경로 (기본값 "~/.config/helm/registry.json")
      --repository-cache string          캐시된 저장소 색인이 포함된 파일의 경로 (기본값 "~/.cache/helm/repository")
      --repository-config string         저장소 이름 및 URL 을 포함하는 파일 경로 (기본값 "~/.config/helm/repositories.yaml")
      --skip-headers                     이 값이 true이면, 로그파일에서 헤더 접두어를 미사용
      --skip-log-headers                 이 값이 true이면, 로그파일을 열 때 헤더 제외
      --stderrthreshold severity         stderr로 로그가 변경될 수 있는 최저 임계점 (기본값 2)
  -v, --v Level                          로그 수준 상세표시 레벨
      --vmodule moduleSpec               파일로 필터링된 로깅을 위한 패턴=N 설정의 쉼표로 구분된 리스트
```

### 참조

* [helm](../helm)	 - 쿠버네티스에 대한 헬름 패키지 매니저.

###### Auto generated by spf13/cobra on 11-May-2020
