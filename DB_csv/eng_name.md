# 교통사고 예방 시스템 시스템 용어 정의

## 용어 정의

- 교통사고 발생 현황 (테이블 이름) : trfacd_status

      교통사고 종류: trfacd_type
      부상 : injury
      사망 : dead

- 교통사고 정보 (테이블 이름) : trfacd_info
      
      교통사고 관리 번호 : trfacd_mngno
      교통사고 날짜 :  trfacd_date
      교통사고 종류 : trfacd_type
      교통사고 발생지 : trfacd_loc

- 교통사고 당사자 (테이블 이름) : trfacd_prt

      당사자 관리 번호 : prt_mngno
      이름 : pname
      성별 : psex
      생년월일 : pbrth
      면허유무 : pdrivSLic
      안전벨트 유무 : psBelt
      부상/사망 여부 : pcasualty
      음주 여부 : pdriking
      사고직전 속도 : pspeed
      사고 관리 번호 :  trfacd_mngno
      교통사고 종류 : trfacd_type

- 지역 구 테이블(테이블 이름) : area

      지역 번호 : anum
      구 이름 :	aname

- 지역별 교통사고 (테이블 이름) : area_trfacd

      지역 사고 번호 : atnum
      지역 번호 : anum
      동 이름 :	dong_name
      사고 지역 CCTV 여부 : cctv
      사고 지역 과속카메라 여부 : scamera
      사고 지역 음주 단속 여부 : sbrtyCheck
      사고 관리 번호 : trfacd_mngno
