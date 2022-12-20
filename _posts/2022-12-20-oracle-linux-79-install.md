---
layout: post
title: "Oracle Linux 7.9 설치"
subtitle: "Oracle Linux 7.9를 설치하는 방법"
date: 2022-12-20 10:00:00 +0900
---

가끔 테스트를 진행하다 보면 Oracle 데이터베이스를 설치해야 하는데 CentOS나 Ubuntu에도 설치는 가능하지만 
설치 준비사항을 충족하는데 꽤 시간이 걸린다. Oracle 데이터베이스 단독 설치의 경우 Oracle Linux를 이용하면 편하게 준비를 할 수 있다.

# Oracle Linux 다운로드
[Oracle Linux ISO Download](https://yum.oracle.com/oracle-linux-isos.html)에 접속하면 원하는 버전의 Full ISO를 
다운로드 받을 수 있다. 이번 포스트에서는 7.9를 설치할 예정이다.

만약, 디스크 공간이 넉넉하지 않고 Minimal Install만 진행할 예정이라면 Boot ISO를 받아도 상관없으나, 
설치과정에서 Repository의 주소를 타이핑해야하는 귀찮음이 존재한다.

# Vritual Machine 생성
최근 사내에 vSphere 서버가 생겨 요즘은 vSphere로 VM을 생성한다. 다른 VM서버도 양식은 비슷하니 참고하여 만들면 된다. 
아무리 테스트 목적의 서버지만 CPU는 2개 이상, 메모리는 4 GB정도가 적당하다. 그리고 위에서 다운로드 받은 ISO를 CD/DVD드라이브에 
설정하고 **전원을 켤 때 연결**을 잊지 말자.

![새 가상 시스템의 하드웨어 설정](https://user-images.githubusercontent.com/100823210/208561487-8be059de-d663-48de-bddb-1c091d75f1e8.png){: width="100%" height="100%"}

**(작성중...)**
