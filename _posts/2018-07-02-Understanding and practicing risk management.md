---

layout: post
title: "[ISMS] 위험관리 이해와 실무"
description: "위험관리 이해와 실무"
date: 2018-07-02
tags: [ISMS, 컨설팅, 보안]
comments: true
share: true

---

**목차**

---

* toc
{:toc}

# 4. 위험관리 이해와 실무
## 1. 위험관리 개요
#### 위험관리<br>
조직의 자산에 대한 위험을 수용할 수 있는 수준으로 유지하기 위해, 자산에 대한 위험을 분석하고 효과적인 보호대책을 마련하는 과정

##### 위험관리의 절차
1. 위험관리 전략 및 계획 수립
2. 위험분석
3. 위험평가
4. 정보보호 대책 선정

<br>

#### 위험분석 방법론<br>
위험분석 방법론은 과학적이고 정형적인 과정으로 위험을 발견 및 측정하려는 노력을 정리한 것, 전 세계적으로 수백여 가지가 존재하만, 실제 분석시 대상 조직의 특징, 요구사항 등에 따라 다양한 방법론을 적용함.

<br>

#### 계량화 여부에 따른 방법 정의
##### 정량적 분석
- 손실크기를 화폐단위로 측정이 가능할 때 사용하는 분석법
- 과거자료 접근법, 수학공식 접근법, 확률분포 추정법

**장점**

- 정량화된 자료의 사용으로 비용-효과 분석 및 예산계획이 쉬움
- 수리적 방법의 사용으로 계산이 논리적

**단점**

- 정확한 정량의 수치를 구하기 어려움
- 수리계산에 많은 시간과 노력이 필요함

<br>

##### 정성적 분석
- 손실크기를 측정할 수 없어서 위험을 구간 및 기술변수로 표현
- 분석자의 경험 및 지식에 기초한 위험분석 방법

**장점**

- 정량화하기 어려운 정보의 평가에 쉬움
- 용어의 이해가 쉬움
- 분석의 소요시간이 짧음

**단점**

- 주관적 판단의 남용 여지가 있음
- 비용-효과 분석이 어려움

<br>

#### 접근방식에 따른 방법 정의<br>
- 위험관리를 하기 위해서는 위험분석이 선행되어야 한다.
- 위험분석을 하기 위해서는 접근방법의 산정이 필요하다.

##### 접근방법
1. 기준선 접근법(Baseline Approach)
   - 모든 시스템에 대하여 보호의 기본수준을 정하고 이를 달성하기 위한 일련의 보호태책 선택
   - 시간과 비용이 많이 들지 않고, 모든 조직에서 기본적으로 필요한 보호대책의 선택 가능
   - 조직 내에 부서별로 적정 보안수준보다도 높게 혹은 낮게 보안통제 적용

2. 전문가 판단법(Informal Approach)
   - 전문가의 지식과 경험에 따라 위험 분석
   - 작은 조직에서 비용 효과적
   - 위험을 제대로 평가하기가 어렵고 보호대책의 선택 및 소요비용을 합리적으로 도출하기 어려움
   - 계속적으로 반복되는 보안관리의 보안감사 및 사후관리가 제한됨

3. 상세위험 접근법(Detailed Risk Approach)
   - 자산의 가치를 측정하고 자산에 대한 위협의 정도와 취약성을 분석하여 위협의 정도를 결정합
   - 조잭 내에 적절한 보안수준 마련 가능
   - 전문적인 지식, 시간, 노력이 많이 소요됨

4. 복합적 접근법(Combined Approach)
   - 먼저 조직 활용에 대한 필수적인, 위험이 높은 시스템을 식별하고 이러한 시스템에는 '상세위험 접근법'을 그렇지 않은 시스템에는 '기준선 접근법'등을 각각 적용
   - 보안전략을 빠르게 구축할 수 있고, 시간과 노력을 효율적으로 활용 가능
   - 두가지 방법의 적용대상을 명확하게 설정하지 못함으로써 자원의 낭비가 발생할 수 있음

<br>

#### 위험관리 절차
1. 위험분석 범위 산정하기
   - 업무, 위치, 자산, 기술적 특성에 따라 위험분석 범위를 산정

2. 위험분석 계획 수립하기
   - 기준선 접근법, 전문가 판단법, 상세위험 접근법, 복합적 접근법 등의 위험분석 방법을 선택하여 위험분석 계획을 수립

3. 조직의 업무와 연관된 정보, 시스템 등의 정보자산을 식별
   - 각 자산의 기밀성, 무결성, 가용성이 상실되었을 때 조직에 미칠 수 있는 영향을 고려하여 자산별 가치를 평가

4. 자산에 대한 위협 및 발생 가능성 정도를 측정
   - 식별된 위험에 대해 각 자산별 실사 또는 인터뷰를 통한 취약점 진단을 수행

5. 자산, 위협, 취약성을 기준으로 위험도를 산출, 기존의 보호대책 점검
   - 산출된 위험도와 기존의 보호대책을 바탕으로 현재 기업이 가지고 있는 잠재적 위험을 평가

6. 위험도를 수용 가능한 위험수준(DoA)까지 낮추기 위한 적합한 보호대책 선정
7. 경감시켜야 하는 위험에 대한 보호대책을 언제, 누가, 어떻게 이행할 것인지 계획 수립
   - 단기, 중기, 장기로 구분되어 마스터 플랜처럼 수립될 수도 있지만, 1년 이내 또는 단기내에 이행이 요구되는 계획은 구체적으로 수립한다.

**이러한 위험관리 절차는 경영진까지 승인을 받는 것이 필요**

<br>

##### 위협과 취약성
- 위협 : 입력오류, 메일폭탄, 해킹, 천재지변으로 전원파괴 등의 위협은 어디에나 있다. 이러한 위협은 보호대책을 통해서 해결할 수 있다.
- 취약성 : 특수권한 관리 미흡, 메일 취약성, 화재발생 등 취약성여부 및 정도에 따라서 위협 상태로 바뀌어지는지의 여부가 결정

**취약성은 현재 가지고 있는 문제점이지만, 위협은 향후 발생 가능한 상황**

- - -

## 2. 정보자산의 중요도 산정
#### 자산 목록 작성<br>
- 위험분석을 하기 위해서는 가장 먼저 무엇을 보호해야할지 식별하기 위한 자산의 목록을 작성하는 것이 필요
- 데이터, 문서, SW, 서버, PC, 네트워크, 시설, 지원서비스, 인력, 매체
- 문서, 시설, 지원서비스, 인력, 매체의 경우 조직의 업무상 이들의 중요도가 낮아 보안상 큰 영향을 미치지 않거나 위험분석을 IT 시스템 중심으로 수행하는 경우라면 세부목록을 작성하지 않을 수 있다.

<br>

#### 자산식별 및 자산 목록표 작성 시 유의사항
1. 자산목록에 꼭 명시해야할 것
   - 누락된 자산이 없도록 완전한 자산파악 실시

2. 조직 전체 자산과 일관성 유지
   - 자산 유형, 식별 번호, 자산 명, 자산의 설명, 소유자(책임자), 관리자, 중요도 산정(등급산정) 등이 명시되어야 한다.

3. 분석이나 진단시 활용하기 위한 추가 정보 포함
   - 서버-응용 프로그램
   - OS 이름

<br>

#### 자산 중요도 산정<br>
- 식별된 자산의 중요도를 산정하고 등급을 선정하는 기준에는 기밀성, 무결성, 가용성, 위협발생가능성, 침해사고 발생시 피해규모, 장애복구를 위한 목표시간이 있다.
- 침해사고가 발생한 경우 기밀성, 무결성, 가용성 측면에서 파악하여 자산의 중요도를 산정하며, 추가적으로 조직의 특성에 따라 비즈니스와 서비스에 영향을 주는 정도를 고려하여 장애복구 목표시간, 법적 준거성 등의 가치평가 항목을 포함시킬 수 있다.

<br>

#### 자산 중요도 평가 기준
1. 기밀성(Confidentiality)
  - 인가된 사람만이 정보자산에 접근할 수 있도록 보장해야 하는 특성
  - 조직의 내부, 외부 공개 범위에 따라 사업 진행에 미치는 영향의 정도로 중요도 평가

2. 무결성(Integrity)
   - 정보자산 내의 정보 및 처리 방법의 정확성과 안정성을 보호해야하는 특성
   - 고의적으로 또는 우연히 변경되는 경우 개인 프라이버시나 조직의 사업진행에 미치는 영향에 따라 중요도 평가

3. 가용성(Availability)
   - 인가된 사용자가 필요 시 정보자산 및 관련 정보에 접근하는 것을 보장해야하는 특성
   - 서비스가 중단되는 경우 운영과 사업 진행에 미치는 영향이 중요도의 산정 기준이 됨

4. 침해사고 발생 시 피해규모
   - 침해사고 발생시 피해교모의 경우 핵심정보서비스의 포함여부와 경제적 손실 수준에 따라 중요도 산정

5. 장애 복구를 위한 목표시간
   - 장애복구를 위한 목표시간 역시 자산 중요도 평가 기준 중 하나
   - 목표시간 : 2시간 이내(중요도 높음)
   - 목표시간 : 2시간 ~ 24시간 이내(중요도 중간)
   - 목표시간 : 24시간 이상(중요도 낮음)

- - -

## 3. 취약점 진단
#### 취약점 진단 절차(관리적/기술적 종합)
- 취약점을 통해 위험요소를 도출해내기 위해서 H/W, S/W, 어플리케이션 자산의 취약점과 조직의 관리적 제도의 취약점을 모두 진단해야 한다.
- 정보보호 현황 분석 > 정보보호 수준 측정 > 스캐닝 도구, 모의해킹 등을 이용한 취약점 분석을 거쳐 취약점을 도출

##### 취약점 분석
- 접근 경로별 취약점
   - 외부(인터넷)에서 내부로의 취약점
   - 내부에서 내부로의 취약점
   - 망 연동시 취약점

- 영역별 취약점
   - 시스템 취약점
   - DB 취약점
   - Application 취약점
   - PC 취약점

#### 취약점 진단
- 물리적 취약점
   - 출입 통제 시스템/직원의 부재
   - 출입구/창문 등의 잠금 장치 미흡
   - 부적절한 장비의 위치 지정

- 환경적 취약점
   - 항온 항습 장치의 부재/미흡
   - 화재 진압 장치의 부재/미흡
   - 침수에 취약한 위치 선정

- 관리적 취약점
   - **운영적 취약점** : 업무절차의 부재/미흡, IR 및 보안 예산의 부족, 장비의 유지보수 미비, 시스템 운영 교육의 부재/미흡, 백업자원과 시스템 및 서비스의 부재/미비 ,업무 연속 계획의 부재 등
   - **정보보호 관리의 취약점** : 정보보호 조직/전담 인력의 부재, 정보보호 정책/지침의 부재, 사고 관리 절차의 미흡, 보안감사의 부재, 보안규정 위반에 따른 징계의 미비, 보안책임 및 권한의 부적절한 부여, 정보보호 교육의 부재/미흡 등
   - **인적 관리의 취약점** : 직원의 부재, 부적절한 직원의 배치, 정규직원 및 제3자 직원의 감독 소홀, 정보보호 인식의 부재, 고용절차의 부적절성

##### 공통 관리 취약점 진단 시 점검항목(예시)

|구분|검토 기준|
|:---:|---|
|정보보호 조직의 구성, 운영|정보보호조직 구성의 적절성, 정보보호책임자의 지정여부 및 업무권한|
|정보보호 계획 등의 수립 및 관리|정보보호 규정 및 계획의 수립, 이행 여부 확인, 정보보호계획에 대한 경영층 승인 여부, 정보보호 실무지침의 마련, 준수, 정보보호 실무지침의 추가적인 검토 보완 여부|
|인원 보안| 내부인력/외부인력/외주용역 보안, 외부인력 활용시 보안서약서 작성 여부, 직무기술서 정의 문서화 여부, 정보보호 교육 및 훈련 실시, 보안인식 향상을 위한 정보보호 정보제공 여부|
|문서 보안| 기술자료 보안관리, 비밀의 생산/분류/보관/파기 등 비밀관리, 중요 프로젝트 수행 시 보안관리|
|정보자산 관리| 모든 정보자산을 파악하고 중요성 판단 여부, 정보자산 분류, 목록 현황 관리 여부|
|보안 점검| 정보보호조치의 자제 보안점검 여부, 자체 보안점검 결과에 따른 이행계획 수립 및 이행 여부|
|침해사고 대응| 침해사고 대응계획의 수립, 침해사고 대응, 복구에 대한 방법 및 절차수립 이행여부|

<br>

#### 서버의 취약점 진단
1. 자산 조사 및 분석
2. 서버 진단 대상 선정(Windows/Linux)
3. 대상에 맞는 관리 담당자 확인
4. 서버 진단 일정 확인
5. 서버 진단 일정 수행
6. 서버 진단 보고서 작성
7. 서버 진단 결과에 대한 보완조치 실시

- Windows 서버
   - 체크리스트 : 윈도우용으로 작성된 체크리스트를 바탕으로 서버에 직접 접속하여 보안성 진단
   - 시스템 배치파일 : 배치파일을 이용하여 Windows 계열의 보안성을 효율적으로 진단

- Linux 서버
   - 체크리스트 : 리눅스용으로 작성된 체크리스트를 이용하여 서버에 직접 접속하여 보안성 진단
   - 시스템 배치파일 : 쉘스크립트를 이용하여 리눅스 시스템의 보안성을 효율적으로 진단

<br>

#### 모의 해킹 진단
1. 대상 선정 : 모의 해킹 수행 대상, 일정, 방법 등 담당자와 협의
2. 프로젝트 수행계획서
3. 정보수집 및 모의해킹
4. 모의해킹 결과보고서
5. 보고서 작성 및 결과발표

##### 모의 해킹 진단 효과
1. 침입자가 각 시스템별로 시스템 관리자 권한 획득 가능성 점검
2. 대상 시스템의 중요 정보 누출 가능성 점검
3. 기타 보안상 취약점 점검

- - -

## 4. 위험 평가
#### 수용 가능한 위험 수준의 결정
##### 위험평가 단계
1. 정보 자산별 위험 분석 결과 도출
2. 정보보호 위원회 구성(정보보호 최고 책임자 참여)
3. 수용 가능한 위험수준 결정
4. 관리되어야 할 위험 통제 방안 마련
5. **조직의 수용 가능한 위험수준(DoA)결정이 매우 중요**

DoA 결정 방법에 표준화된 방법론이 없기 때문에, 정보보호 최고 의결 기구에서 최대한의 객관적 판단을 유도하여 DoA를 결정하는 것이 좋다. DoA가 결정되면 이에 따라 관리되어야 할 위험과 잔여위험에 대한 통제방안을 마련하게 된다.

<br>

#### DoA에 따른 위험처리 방안
- 위험수용
   - 현재의 위험을 받아들이고 잠재적 손실 비용 감수
   - 일정수준 이하의 위험은 감수하고 사업 진행
- 위험모니터링
   - 잠재위험이 위험요인으로 변화가 가능하므로 지속적인 모니터링 실시
   - DoA 주변의 위험도가 위험 모니터링의 대상이 될 수 있음
- 위험감소
   - 직접적인 피해가 발생할 수 있는 중대한 위험은 잠재하고 있어 정보보호대책을 선택하여 구현
- 위험회피
   - 위험이 존재하는 프로세스나 사업을 수행하지 않고 포기
- 위험전가
   - 보험이나 외주 등으로 잠재적 비용을 제3자에게 이전하거나 할당

- - -

## 5. 정보보호대책 선정 및 정보보호 계획 수립
정보보호 대책 선정 > 정보보호 이행 계획 수립
도출된 위험 분석 결과 > 가상의 사니라오 작성 > 가장 적합한 보호대책 도출

<br>

#### 보호대책의 속성
- 단기, 중기, 장기 적용대책을 구분하여 보호대책을 수립
- 중기, 장기 적용대책은 정보보호계획서 또는 보안 마스터플랜 등을 통해 계획을 수립
- 보호대책 수립은 다음과 같은 속성을 갖는다.
   - 현존하는 위협으로부터 자산을 보호해야 함
   - 보호대책이 증가할수록 취약점 감소하지만 취약점은 0이될 수 업음
   - 보호대책은 위협의 발생으로 인한 피해를 감소시키고 유형에 따라 위협의 주기도 감소시킴

<br>

#### 보호대책 선정 시 고려사항
1. 위험관리를 허용하는 기간 내에 이루어질 수 있도록 수립
   - 주요 자산이 위험에 노출되도록 남겨 둘 수 있는 허용기간 내에 수립
   - 위험을 수용할 수 있는 기간 내에 보호대책이 실행될 수 있도록 수립
2. 보호대책을 선정할 때에는 예산 고려
   - 보호대책 수립, 구현, 유지 비용은 합리적 예산 내 처리
   - 처리 비용 보다 높은 보호 수준이 요구될 경우 ,비용이 자산의 가치보다 높을 수 있음
3. 기술적인 문제 고려
   - 프로그램 및 하드웨어와의 호환성
   - 기술구현 용이
4. 조직의 사회적 환경 고려
   - 조직의 목표, 업무특성, 사회적 책임, 조직의 철학과 비전, 동종업계 상황
   - 관련 법규 반영
5. 기대효과 분석을 통해 제한된 비용으로 최적의 효과 고려
   - 위험요소를 점검하여 위험요소를 제거, 최소화할 수 있는 개선대책 마련
   - 유사사례에 대한 벤치마킹을 통해 최악의 상황을 대한 조치사항, 책임사항 준비
   - 위험요소에 대한 점검 및 개선을 위한 총괄 계획표 작성

<br>

#### 정보보호대책명세서 작성
- 정보보호대책멩세서는 인증기준 104개를 기준으로 현재 적용되거나 또는 앞으로 적용될 보호대책을 문서화를 통해 정의한 것
   - 104개 인증기준 항목에 대해 현재 운영현황을 구체적으로 명시
   - 정보보호대책 13개 분야별 92개 인증기준 중 선택하지 않은 것이 있다면 이유를 명확하게 기술
- 목적 : 전반적인 정보보호 현황 파악, 장기적으로 타 조직과의 협업 등에 사용

##### 정보보호대책명세서 작성 예시

<img src="/assets/images/ISMS/4-1.png" width="100%">

- 선정된 정보보호대책의 명세 포함
- 구현 확인 근거 포함
- 선정되지 않은 정보보호대책 목록과 근거 포함

<br>

#### 정보보호 계획 수립 절차
1. 요구사항 분석 : 관리적, 기술적, 물리적 측면의 정보보호 요구사항
2. 정보보호 모델 수립
3. 단기과제 선별 : 취약점 또는 위험에 대해 1개월 이내 빠른 조치가 가능한 과제
4. 중장기과제 선별 : 6개월에서 1년 이상의 기간이 소요되는 과제
5. 세부이행계획수립

**효과성과 시급성에 따른 우선순위와 각 특성들을 고려하여 대책을 구현해야한다.**

특성과 목적이 유사한 대책들은 하나의 프로젝트로 묶어 쉬운 구현 가능

- 즉시 교정 가능한 취약점 제거
- 정책 및 절차 수립
- 분야별 정보보호 시스템 도입 및 관련 교육 수행
- 모니터링 및 감사 관련 사항