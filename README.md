- nifi.flow.configuration.file
- nifi.database.directory
- nifi.flowfile.repository.directory
- nifi.content.repository.directory.default
- nifi.provenance.repository.directory.default

위 5가지 config를 수정할 수 있도록 이미지 수정.

yaml 파일에 아래와 같이 env 추가
```
- name: NIFI_PROVENANCE_REPOSITORY_DIRECTORY_DEFAULT
  value: "/data/provenance_repository"
```
