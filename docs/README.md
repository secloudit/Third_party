# Secloudit Third party repository

Secloudit 수정 필요 Third Party Code 저장소

## 연동 방법
```cassandraql
$ vim go.mod
replace ( 
  knative.dev/pkg => github.com/secloudit/third_party/knative.dev/pkg latest
  github.com/tektoncd/pipeline => github.com/secloudit/third_party/github.com/tektoncd/pipeline latest
)
추가
```

## Third Party 코드 관리 상황

| <center>모듈</center> | <center>submodule</center> | <center>버전관리 github</center> |
|:-------|:------:|------:|
| <center>tektoncd/pipeline</center> | <center>O</center> | <center>[Tekton Pipeline](https://github.com/Jin-Whee-Park/pipeline)</center> |
| <center>knative/pkg</center> | <center>O</center> | <center>[Knative pkg](https://github.com/Jin-Whee-Park/pkg)</center> |


## 참고 
* tektoncd/pipeline : [Tekton Pipeline] (https://github.com/tektoncd/pipeline)
* knative.dev/pkg : [knative/pkg] (https://github.com/knative/pkg)

