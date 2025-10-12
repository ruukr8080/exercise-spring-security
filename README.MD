- 📁sub : h1, h2 주제
- 📖index : (summary) 해당 주제의 핵심 개념
- 🔥FORGE : (대장간) 학습한 개념을 실습하는 과정을 의미합니다.
  - 📜Project : 실습합니다.

```
💻Labs-Spring:./
   ├─📁JPA
   │    ├─📂CRUD
   │    ├─📂Data-Relation
   │    └─🔥FORGE
   ├─📁Security
   │    ├─📖index(구조와 흐름,Bean,주요 인터페이스,메서드)
   │    ├─📂Advance
   │    │     └─📂Web-Security
   │    │           ├─📖index(OSI7-MAC~TCP,IP)
   │    │           ├─📂HTTPS
   │    │           │    └─📂MITM
   │    │           │         ├─📄암호화와 인증서
   │    │           │         ├─📄Spoofing
   │    │           │         ├─📄Sniffing
   │    │           │         ├─📄XSS공격과 방어
   │    │           │         ├─📄CSRF공격과 방어
   │    │           │         └─📄CI 보안 강화 설계
   │    │           └─🔥FORGE
   │    │                ├─📜CSRF 공격 구현
   │    │                ├─📜Filter_공격 구현
   │    │                ├─📜Session_공격 구현
   │    │                └─📜Session_방어 구현
   │    │
   │    ├─📂Jwt
   │    │    ├─📖index(JJwt_11.5 / 12.6)
   │    │    ├─📖index(nimbus-jose-jwt:10.4.2)
   │    │    ├─📜JJwt(JwtBuilder기반 생성,검증)
   │    │    ├─📜Nimbus-JWT(Clame기반 생성,검증) JWS
   │    │    ├─📜JWS
   │    │    └─🔥FORGE
   │    │        ├─📜Jwt_취약점 공격 구현
   │    │        ├─📜Jwt_방어 강화
   │    │        ├─📜PKCE 생성, JWK 검증
   │    │        └─📄시나리오 스크립트
   │    │
   │    └─📂Oauth
   │         ├─📖index(구조,보안고려사항)
   │         ├─📖index(Oauth2.1)
   │         ├─📂basic+Extend
   │         │     └─📄google
   │         ├─📂Oauth2.1
   │         │     └─📄Oauth2.1(PKCE, 인증/인가 모듈 분리)
   │         └─🔥FORGE
   │              ├─📜Jwt(Claim기반)+Oauth2.1
   │              ├─📜SRP,OCP 중점 설계
   │              └─📜Redis 안정성 향상
   └─📁Network
        └─📂Socket

```

### 🌴Reference

## 📁Security

▶ [`docs.spring.io`](https://docs.spring.io/spring-security/reference/servlet/architecture.html#servlet-filterchainproxy) : Security Framework-FilterChainProxy

▶ [`ibm.com`](https://www.ibm.com/docs/ko/sva/11.0.0?topic=control-overview-api-access) : IBM의 API서버 접근 제어 방식. `WebSEAL 시스템`

▶ [`connect2id.com/`](https://connect2id.com/) , [`datatracker.ietf.org`](https://datatracker.ietf.org/doc/draft-ietf-oauth-v2-1/) : OAuth2.1 권장 최소 보안 기준선과 통합 인증객체(open_id_token)구조
