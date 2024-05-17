# testcpp

sudo /var/lib/docker/volumes/tez_ok_sonarqube_data/_data/sonar-scanner-5.0.1.3006-linux/bin/sonar-scanner \
  -Dsonar.projectKey=testcpp \
  -Dsonar.sources=. \
  -Dsonar.host.url=http://0.0.0.0:9000 \
  -Dsonar.token=sqp_c08ec1f6efe09f12e6d753ff69410fb83f5e3e79\
  -Dsonar.cxx.file.suffixes=.h,.cpp