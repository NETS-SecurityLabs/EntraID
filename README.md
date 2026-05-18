# 소개: EASM 탐지 로그인 페이지와 Entra ID 인증 통합

최근 EASM(External Attack Surface Management) 솔루션을 통해 조직 외부에 노출된 다양한 로그인 페이지가 탐지되고 있습니다. 이러한 로그인 페이지를 Microsoft Entra ID(구 Azure AD) 기반으로 인증을 통합하면 다음과 같은 보안 효과를 얻을 수 있습니다.

- **공격 표면 감소:** 외부에 노출된 개별 로그인 페이지의 인증 체계를 Entra ID로 통합함으로써, 불필요한 계정 관리와 취약점 노출을 최소화할 수 있습니다.
- **조건부 접근 정책 적용:** Entra ID의 조건부 접근(Conditional Access) 정책을 통해 사용자, 위치, 장치 상태 등 다양한 조건에 따라 접근을 제어할 수 있습니다.
- **MFA 및 세션 보안:** 다단계 인증(MFA)과 세션 제어 등 고급 보안 기능을 손쉽게 적용할 수 있습니다.
- **향후 확장성:** 장치 관리, 세션 보호, ID 보호 등 추가적인 보안 환경 구축의 첫 관문이 됩니다.

> **Entra ID 인증 통합은 조직의 외부 공격 표면을 줄이고, 체계적인 접근 통제와 확장 가능한 보안 환경을 마련하는 핵심 출발점입니다.**

---

# Entra ID 기반의 인증 통합으로 보안 강화하기

본 저장소는 "Entra ID 기반의 인증 통합으로 보안 강화하기" 세미나 발표 자료와 Hands-on Labs 실습 모듈을 제공합니다.

## Hands-on Lab 목차
Entra ID를 중심으로 SaaS에 대한 인증 통합을 구성하는 실습입니다.

1. [EID Lab 사전 준비사항](EID%20Lab%20사전%20준비사항.md)
2. [EID Step01 - IdP에 App 등록 및 구성](EID%20Step01%20-%20IdP(Entra%20ID)에%20App%20등록%20및%20SP%20정보%20입력.md)
3. [EID Step02 - SP에 IdP 연동](EID%20Step02%20-%20SP(Salesforce)에%20IdP(Entra%20ID)%20정보%20등록.md)
4. [EID Step03 - 통합 인증 테스트](EID%20Step03%20-%20Login%20Test.md)

---

본 저장소의 자료는 교육 및 실습 목적으로만 사용해 주시기 바랍니다.
