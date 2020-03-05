What's New for Autonomous Data Warehouse
===
https://docs.oracle.com/en/cloud/paas/autonomous-data-warehouse-cloud/whats-new/index.html#CSWHN-GUID-F31A86F8-012B-4235-A0BE-4ABF75164853

* April 2018
   - Microsoft Azure Blob Storage integration 
데이터 로딩과 외부 데이터에 대한 쿼리를 위해 마이크로소프트 Azure의 Blob Storage를 지원함.
Azure Blob Storage에 있는 파일에 대해서 데이터 로딩과 쿼리를 실행할 수 있음
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-07900054-CB65-490A-AF3C-39EF45505802
   - Manage files on the local file system
로컬 파일 시스템을 조회할 수 있음
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-78F49B25-C072-45E1-BE83-E306ACC998EE
그리고 로컬 파일 시스템의 파일을 지우기도 가능함
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-930632E1-B7BF-4ECA-8F78-5E5A205C0865

---

* May 2018
---
- Oracle Cloud Infrastructure Object Storage Credentials
Swift 패스워드의 이름은 지금부터 Auto token이라고 함. Swift password라는 이름은 모두 Auth token으로 변경함.

* June 2018
---
- New management interfaces
지금부터 native OCI위에 프로비저닝 됨.
ADW 인스턴스 관리를 쉽게만들기 위해 정렬, 필터링 기능을 포함한 추가적인 기능과 함께 이해하기 쉬운 유저 인터페이스를 제공함
https://docs.oracle.com/en/cloud/paas/autonomous-data-warehouse-cloud/index.html

- Better authorization management 
사용자 그룹이나 타입에 따른 접근성 제어와 컴파트먼트를 사용하는 IAM을 이용해서 ADW 인스턴스에 대한 보다 나은 구성과 고립을 할 수 있음.
http://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud&id=oci-iam

- Built-in auditing
OCI Audit service가 ADW API의 JSON 포맷으로 된 로그 이벤트를 사용함
사용자는 이것을 로그 분석기, audit 서비스 콘솔, audit api, java sdk 등을 사용해서 확인, 복사, 분석 등을 할 수 있음
http://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud&id=oci-audit-service

- Availability of the Phoenix region
기존 애쉬번과 프랑크푸르트에 피닉스 리전을 추가

- User Assistance changes
도큐먼트, 비디오, 사용예제가 업데이트 됨
클라우드 포럼을 포함한 관련된 리소스를 보여주는 페이지가 추가됨
https://cloudcustomerconnect.oracle.com/resources/32a53f8587/summary

- Idle timeouts in database services
Idle 세션에 대해 5분의 timeout 설정이 적용됨
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-80E464A7-8ED4-45BB-A7D6-E201DD4107B7

* July 2018
---
- SQL Developer 18.2.0 and later without Keystore Password field for connections
SQL Developer 18.2.0 또는 그 이상 버전을 사용한 ADW 접속 시, 더 이상 keystore 패스워드가 필요하지 않음

* August 2018
---
- The Oracle Cloud Infrastructure page has a new option Autonomous Transaction Processing 
Autonomous Transaction Processing 서비스가 추가됨

* September 2018
---
- Table compression methods
ADW에 Hybrid Columnar Compression 외에도 모든 유형의 테이블 압축 유형을 사용 가능함
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-E2E72DF9-00A3-47EE-BC39-22509E0FF8BE

- Partitioned tables, indexes, and materialized views
사용자는 이제 파티션 테이블, 인덱스, Mview를 생성할 수 있음
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-4D0364B5-8CA1-4A38-83AE-05B1C9487465

- Idle timeout changes
Idle 타임아웃 시간이 60분으로 변경됨
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-80E464A7-8ED4-45BB-A7D6-E201DD4107B7

* October 2018
- Oracle Cloud Infrastructure Console changes
새로운 레이아웃과 버튼을 배치하고 DB Connection에 사용하는 client credentials를 쉽게 다운로드 할 수 있도록 변경함

- Documentation changes
ADW Documentation가 사용자 Role Base로 변경됨

* January 2019
---
- Access Parquet files in Object Stores
ADW는 Object 스토리지에 저장되어 있는 parquet 파일에 직접 쿼리하거나 데이터를 불러 올 수 있음
또한 External parquet 테이블을 오브젝트 스토리지에 생성 가능함
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-55DE445F-50E6-430D-87AB-C8DDC6D9810F
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-D23C5CEF-770C-436D-B856-4C6C318FA045

* February 2019
---
- Application Continuity
Application Continuity를 활성, 비활성이 가능해짐
Application Continuity는 실행 중인 작업 중에서 서비스 중단 후 영향을 받는 데이터베이스 세션을 복구함으로써 최종 사용자와 어플리케이션을 마스킹함
Application Continuity는 어플리케이션 아래에서 복구를 수행하고 이것은 outages를 약간의 지연 실행정도로 보이게 함
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-8874CB1D-0B20-461F-91D2-24E2EE4148A3

- Documentation changes
다른 Oracle Database로의 데이터 이동 챕터가 추가됨
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-529CD03E-7983-423B-A5FD-34D8B36831EC

* March 2019
---
- Clone Your Database
ADW는 Full Database 또는 DB Metadata만 사용하는 DB Cloning을 지원함
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-D771796F-5081-4CFB-A7FF-0F893EABD7BC

- Oracle Cloud Infrastructure Native URI Format Supported with DBMS_CLOUD
Source 파일이 OCI Object 스토리지에 있다면 Swift URI 외에도 OCI native URI를 사용할 수 있음
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-5D3E1614-ADF2-4DB5-B2B2-D5613F10E4FA

- UI/API Unification and Workload Type field
ADW와 ATP를 위한 OCI 콘솔과 OCI API는 단일 프레임워크로 전환함
이 변화는 사용자를 Autonomous Database를 관리하기 쉽게 만들어 줌 
콘솔에 DB Type에 따른 Workload Type 표시 필드를 새로 생성하였으며 이것은 Transaction Processing 또는 Data Warehouse를 보여줄 것임
DB Type(Workload Type)은 프로비저닝 할 때 선택할 수 있음
https://docs.cloud.oracle.com/iaas/Content/Database/Concepts/adboverview.htm?Highlight=workload%20type
 
- Service Gateway
ADW에 Service Gateway를 셋업 가능함
Service Gateway는 ADW를 Private subnet에 있는 Private IP에서 VCN의 Internet Gateway를 거치지 않고 연결할 수 있는 기능
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-76D412D4-03F4-49BA-B70C-DEA70B11AC34
https://docs.cloud.oracle.com/iaas/Content/Network/Tasks/servicegateway.htm

- Documentation changes
프로시저 DBMS_CLOUD.DELETE_ALL_OPERATIONS가 업데이트
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-CEC0CA63-B77F-4D64-B70F-1E8476AE3ED6

* April 2019
---
- Support for Network Access Control Lists
접근 제한을 위한 Network Access Control List(ACL)을 제공함
ACL을 설정하면 ACL에 등록된 주소에 대해서만 DB 접근을 허용함
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-AFA6FE4D-E4E7-4064-A960-0BB2E51A692A

- Support for Updating License Type
License Type 업데이트 됨
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-AFA6FE4D-E4E7-4064-A960-0BB2E51A692A

- Access Avro files in Object Stores
Apache Avro format file에 대해서 직접 쿼리 및 데이터 로딩이 가능해짐
또한 External Table을 Parquet 또는 Avro의 데이터 파일에 만들 수 있음
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-517B1FA2-5810-4BF8-B9B0-4E912CA034C3
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-D23C5CEF-770C-436D-B856-4C6C318FA045

- Enhanced newline handling for file record delimiter with DBMS_CLOUD
파일을 읽을 때 DBMS_CLOUD는 기본적으로 newline 문자를 delimiter로 사용하기 위해 찾음(윈도우즈는 "\r\n", UNIX/LINUX는 "\n")
DBMS_CLOUD가 newline 문자를 파일에서 찾으면 delimiter로 설정하고, 사용자가 임의로 delimiter를 원하는 것으로 override할 수 있음
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-08C44CDA-7C81-481A-BA0A-F7346473B703

- Modify CPU/IO Shares
워크로드가 서로 다른 CPU/IO share를 필요로 할 때 사용자는 미리 지정된(predefined) CPU/IO share를 다른 consumer group에 할당할 수 있음
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-8FEE49FF-CDEE-4433-B812-0AAABA8DEC7F

* May 2019
---
- Support for creating database links
DBMS_CLOUD_ADMIN.CREATE_DATABASE_LINK를 사용해서 DB Link를 생성할 수 있고 다른 데이터베이스 오브젝트에 접근이 가능해짐
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-28F06977-300F-4599-AD97-2DEF67EF5FEA

- Oracle Spatial and Graph with limitations
ADW에서 Spatial&Graph를 제한적으로 사용 가능함
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-DAE5CF82-FD27-407B-8B1F-CC376A5DBD6F

- Oracle Text with limitations
ADW에서 Oracle Text를 제한적으로 사용 가능함
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-5BB6999D-F44D-4C9E-9F57-F2EBBEFF202C

- Oracle Cloud Infrastructure Native URI Format Supported with Oracle Data Pump
Data Pump에서 impdp로 데이터를 로딩할 때 OCI Object Storage에 원본 파일이 있다면 Swift URI와 OCI native URI를 사용할 수 있음
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-5D3E1614-ADF2-4DB5-B2B2-D5613F10E4FA

- Oracle XML DB with limitations
Oracle DB의 한 파트로써 Oracle XML DB는 고성능, native XML 스토리지, 검색 기술을 제공함
ADW에서는 제한적으로 사용할 수 있음
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-BA0CCEA1-800F-44B0-816E-9C3A6156503E

- Oracle Management Cloud support 
Oracle Management Cloud를 통해 퍼포먼스와 가용성 모니터링을 할 수 있음
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=MCDBM-GUID-1BCBB1FD-035A-4005-A6EA-CD6A89172431

- Modify CPU/IO Shares from Service Console
PL/SQL package 뿐만 아니라 서비스 콘솔에서도 CPU/IO share를 조정할 수 있음
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-8FEE49FF-CDEE-4433-B812-0AAABA8DEC7F

* June 2019
---
- Application Express (APEX)
APEX는 확장, 보안 등 세계 표준 기능과 함께 어디서든 배포할 수 있는 기업용 어플리케이션을 위한 low-code 개발 플랫폼임
각 ADW 인스턴스는 APEX의 독립적인 인스턴스를 포함하고 있음; 이것을 이용해서 멀티 워크스페이스를 만들 수 있음
워크스페이스는 어플리케이션을 build할 수 있는 공유 작업 영역임
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-F275EA9F-F9A4-4A72-B777-5548362FDDA5

- SQL Developer Web
SQL Developer Web은 ADW를 위한 개발 환경, 데이터 모델러 인터페이스를 제공함
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-C32A78E5-4C5F-476F-86AB-AEEEA9CF2704

- Oracle REST Data Services (ORDS)
사용자는 ADW를 지원하는 native Oracle REST Data Services(ORDS)를 통해 RESTful 서비스를 개발하고 배포할 수 있음
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-E2E921FF-2D80-4E32-9660-28506D10BADB

- Auto Scaling
Auto scaling은 ADW의 현재 명시된 CPU/IO 자원을 최대 3배까지 사용할 수 있게 함(최대 128 CPU Core)
Auto scaling이 활성화되면 추가적인 CPU/IO 자원을 요구하는 워크로드를 사용자의 수작업이나 개입없이 DB가 자동으로 추가 자원을 사용함
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-AFA6FE4D-E4E7-4064-A960-0BB2E51A692A

- Azure object store with Data Pump
ADW는 MS Azure storage에서 Data Pump를 이용한 Import를 지원함
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-30DB1EEA-DB45-49EA-9E97-DF49A9968E24

* July 2019
---
- Performance Hub
OCI 콘솔은 ADW를 위한 Performance Hub를 포함함
사용자는 퍼포먼스 허브를 사용해 실시간 퍼포먼스와 과거 퍼포먼스 데이터를 확인할 수 있음
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-1EA329A7-3875-477E-B656-18F191D8C4B1

- Oracle Cloud Infrastructure Native Object StoreAuthentication
ADW는 OCI Object Store에 있는 native authentication을 지원함
Native authentication를 사용하면 key 베이스의 인증을 Object Store에 접근하는데 사용할 수 있음
(username, password 방식을 사용할 필요 없음)
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-742FC365-AA09-48A8-922C-1987795CF36A

- Move to a different Compartment
ADW를 다른 OCI Compartment로 이동할 수 있음
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-D3E6A489-D125-4339-9D23-BAE52DFE512E

* August 2019
---
- Create Directory and Drop Directory commands
DATA_PUMP_DIR 디렉토리를 ADW에서 사용 가능함
CREATE DIRECTORY 명렬을 사용해 추가 디렉토리를 생성할 수 있고, DROP DIRECTORY를 사용해 디렉토리를 삭제할 수 있음
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-5EC418F4-2084-4884-8D1E-BACA56F143F9

* September 2019
---
- Always Free Autonomous Database 
Cloud Credit을 소모하지 않고 제한된 수의 무료 Autonomous Database를 생성하는 옵션을 제공함
무료 Autonomous Database는 계정이 Trial 기간이거나, UC 계약 중에 관계없이 항상 무료로 제공됨
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-03F9F3E8-8A98-4792-AB9C-F0BACF02DC3E

- Object Store Using Public URL
원본 파일이 Public URL을 제공하는 Object Store에 있으면 DBMS_CLOUD 프로시저를 사용해 public URL를 이용 가능함
Public은 Object Storage 서비스가 이름, 인증 없이 Object Store의 파일을 사용하는 것을 의미함
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-5D3E1614-ADF2-4DB5-B2B2-D5613F10E4FA

- Work Requests
Work Requests는 OCI 콘솔에서 사용할 수 있음
Work Requests는 Database lifecycle 관리 명령을 추적하여 진행 정도나 완료를 사용자에게 알려줌
가령 ADW에 실행된 생성, 제거, 백업, 복구, 스케일링, 복제 등의 명령이 있음
https://www.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-32773B4E-B918-4F19-87FC-C44C2EE63E8C

* October 2019
---
- Preview Version for Autonomous Database
오라클은 주기적으로 ADW의 미리보기 버전을 제공합니다. 이것은 어플리케이션 테스트를 할 수 있고 또한 새로운 버전의 신기능에 익숙해지도록 합니다.
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-D1288B3D-6926-4244-B65A-E9E1FF4DAE5A

- Download database specific instance wallets or regional wallets
특정 인스턴스의 Wallet을 다운로드 가능함
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-B06202D2-0597-41AA-9481-3B174F75D4B1

- Rotate database specific instance wallets or regional wallets
특정 인스턴스의 Wallet을 로테이션 할 수 있음
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-F0995A6A-78BD-4C9D-9A34-B970BD152CAD

- Create partitioned external tables with DBMS_CLOUD 
DBMS_CLOUD.CREATE_EXTERNAL_PART_TABLE, DBMS_CLOUD.VALIDATE_EXTERNAL_TABLE을 사용해서 External Partition Table을 생성하고 사용할 수 있음
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-1399BCF7-05E6-49FE-8710-7571DDF49E39

- Numeric Formats
Number 형식과 Numeric Character 형식은 ADW에서 Numeric String으로 자동 교정을 지원함
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-08C44CDA-7C81-481A-BA0A-F7346473B703

* November 2019
---
- Use ACLs to specify Oracle Cloud Infrastructure VCNs 
ADW에 연결한 OCI VCN을 통해서 ACL을 사용할 수 있음
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-B6389402-3F4D-45A2-A4DE-EAF1B31D8E50

- SQL Developer Web Data Loading
SQL Developer Web의 Worksheet에서 로컬 파일(CSV, XLSX 등)을 ADW의 Table에 업로드 할 수 있음
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-25CEEF91-ACE7-47BF-AF0A-4F4964018719

- Access APEX from Oracle Cloud Infrastructure Console 
OCI Console의 Tool Tab에서 APEX에 접속이 가능함
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-D078638E-4F59-46CA-A14D-DAEBE1514BE8

- Access SQL Developer Web from Oracle Cloud Infrastructure Console 
OCI Consloe의 Tool Tab에서 SQL Developer Web에 접속이 가능함
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-0D93A57B-193B-43F0-BDE2-174BC3E13FCC

- Access Oracle Machine Learning from Oracle Cloud Infrastructure Console 
OCI Console의 Tool Tab에서 Oracle Machine Learning User Administration에 접속 가능함
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-0F489564-A628-478E-9898-1F94B0441026

- View Maintenance Schedule from Oracle Cloud Infrastructure Console 
Autonomous Database Information Tab에서는 예정된 메인터넌스 스케쥴을 확인 할 수 있음
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-C4F488BA-C2ED-4890-A411-9F99C69CD8DF

- New fields with LIST_FILES and LIST_OBJECTS
DBMS_CLOUD.LIST_FILES, DBMS_CLOUD.LIST_OBJECTS을 사용해서 추가적은 파일이나 오브젝트를 위한 메타데이터를 추가 가능함
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-78F49B25-C072-45E1-BE83-E306ACC998EE

* December 2019
---
- Support for UTL_HTTP and UTL_SMTP PL/SQL Packages with restrictions 
ADW는 UTL_HTTP, UTL_SMTP, DBMS_NETWORK_ACL_ADMIN을 일부 제한 사항과 함께 제공함
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-829A7D07-1EA4-4F59-AA60-F780FABAFDEC

- Microsoft Active Directory Users
ADW에 Microsoft의 Active Directory 사용자의 권한과 인증을 구성할 수 있습니다.
이것은 Active Directory의 Credential을 사용해서 AD 사용자가 ADW에 접근할 수 있게 합니다.
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-11754210-CCD7-48B3-BC16-0E537A27217C

- Validate external partitioned tables and hybrid partitioned tables
DBMS_CLOUD.VALIDATE_EXTERNAL_PART_TABLE, DBMS_CLOUD.VALIDATE_HYBRID_PART_TABLE 프로시저를 사용해서
External Partition Table 또는 Hybrid Partition Table의 개별 파티션을 유효화 할 수 있음.
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-30B5D898-DC3B-4004-B601-EE55D754FDFD

- Use ACL IP address or CIDR block settings to control access for Autonomous Database tools 
IP, CIDR 기반의 ACL을 사용해서 APEX, RESTful 서비스, SQL Developer Web에 접근 제어를 할 수 있음
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-B6389402-3F4D-45A2-A4DE-EAF1B31D8E50

- Use Oracle Data Safe
ADW 내에 보호 대상 데이터에 대해 Oracle Data Safe 기능을 제공함
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-2D36B6A7-BA83-4F75-A46C-51E419D4D3AA

* January 2020
---
- Clone from a backup
Backup 리스트 또는 Point-in-time Timestamp로부터 Backup의 복제본을 생성할 수 있음
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-20D2D970-0CB4-472F-BF89-1EE769BFB5E8

- Check and set MAX_STRING_SIZE value 
ADW는 기본적으로 확장 데이터 타입의 사용이 가능하고 MAX_STRING_SIZE가 EXTENDED입니다.
구버전 데이터베이스/어플리케이션의 마이그레이션 지원을 위해 MAX_STRING_SIZE를 STANDARD로 설정할 수 있습니다.
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-7340C837-FD5F-489D-9348-A4E86846323F

- Number of concurrent statements increased depending on the service you use
동시성 구문의 최대 수를 사용자가 사용하는 연결 서비스에 따라 증가 가능합니다.
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-9747539B-FD46-44F1-8FF8-F5AC650F15BE

- Documentation addition showing available Oracle Database versions
지역에 따라 ADW의 사용 가능한 버전을 Documentation에서 확인할 수 있습니다.
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-882460C7-EFCD-4E7E-B115-A7239E4CC406

- DBMS_CLOUD REST API functions 
DBMS_CLOUD REST API 기능으로 DBMS_CLOUD.SEND_REQUEST를 사용해 HTTP request를 만들수 있습니다. 
이 기능은 REST API를 호출하는 것과 같은 일반적인 API도 제공합니다.
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-19B1639E-68E2-45BB-802C-817ABD0DBE88%20%20

- Documentation addition to describe sending mail with UTL_SMTP
UTL_SMTP를 이용한 E-MAIL 발송 샘플 코드가 Documentation에 업데이트 되었습니다.
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-B64E0087-5606-4B60-9D6A-CF09F22C7CEC

- Use ACLs to control access for Autonomous Database tools 
VCN, VCN(OCID), IP, CIDR Block를 사용한 ACL을 통해 ACL을 사용해서 APEX, RESTful 서비스, SQL Developer Web에 접근 제어를 할 수 있습니다.
https://docs.oracle.com/pls/topic/lookup?ctx=en/cloud/paas/autonomous-data-warehouse-cloud/whats-new&id=CSWHU-GUID-B6389402-3F4D-45A2-A4DE-EAF1B31D8E50

