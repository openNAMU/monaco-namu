## 본론
추후 오픈나무마크에 대한 monaco editor syntax를 완성할 계획이 있으나 아직은 미완성 상태입니다

그래서 이러한 불편함을 임시로 해소하고자 [monaco-namu](https://github.com/namu-wiki/monaco-namu)의 [openNAMU Addon](https://github.com/openNAMU/openNAMU-Addon-monacoNamu)을 제작하였습니다

## 사용 가능 버전
 * v3.5.0-v119 이상

## 사용 방법
`메인 <HEAD>`에다가 `<script defer src="https://cdn.jsdelivr.net/gh/opennamu/monaco-namu@master/namu/vs/languages/namumark.js"></script>` 을 추가하면 됩니다

## 주의사항
 * 해당 Addon은 AGPL이므로 **소스 코드를 따로 수정해서 쓰는 경우 무조건 재배포 해야합니다**
 * 해당 Addon은 AGPL이므로 **CDN이 아닌 로컬 서버에 올려서 같이 돌리는 경우 라이선스 전염이 될 수 있으니 안하는 게 좋습니다**
