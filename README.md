## AWS 기반 서버리스 백엔드
- AWS Lambda, API Gateway, EventBridge, S3를 기반으로 플랫폼의 백엔드를 구성하였습니다.
- AWS Lambda 함수 중 주요 함수를 일부 공개합니다.
- 함수명 앞에 'fd-'가 적힌 함수는 보호자 및 의사용 앱과 연결되며, 그렇지 않은 함수는 본인용 앱과 연결됩니다.
- 코드는 code_lastest.zip의 압축을 풀어 확인하실 수 있습니다.

## Directory Structure
- `functions/<NAME>/` : code_lastest.zip, get-function.json, config.json, versions.json, aliases.json, event-source-mappings.json, policy*.{json,txt}, code_sha256.txt
- `layers/<LAYER>/<VER>/` : meta.json, policy*.{json,txt}
> Large binaries (tgz, jars, etc.) are excluded via `.gitignore`.
