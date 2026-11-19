# 프록시 요금제를 사기 전에 볼 짧은 목록

이 목록은 Northleaf Studio가 발행합니다. Northleaf Studio는 [ProxyVendors](https://proxyvendors.com/ko/)도 운영합니다. 같은 운영자의 보조 자료이며, 무관한 제삼자의 추천이 아닙니다. 사업자의 현재 가격 페이지, 약관, 작은 시험에 맞춰 사용하십시오. 어떤 요금제가 여러분의 대상에서 반드시 동작한다고 보장하지는 않습니다.

## 언어

- [English](../../guides/buying-checklist.md)
- [简体中文](../../zh-cn/guides/buying-checklist.md)
- [Español](../../es/guides/buying-checklist.md)
- [Deutsch](../../de/guides/buying-checklist.md)
- [Français](../../fr/guides/buying-checklist.md)
- [日本語](../../ja/guides/buying-checklist.md)
- [Português](../../pt/guides/buying-checklist.md)
- **한국어**
- [اردو](../../ur/guides/buying-checklist.md)
- [Bahasa Indonesia](../../id/guides/buying-checklist.md)
- [Türkçe](../../tr/guides/buying-checklist.md)
- [العربية](../../ar/guides/buying-checklist.md)
- [Polski](../../pl/guides/buying-checklist.md)
- [Italiano](../../it/guides/buying-checklist.md)
- [ไทย](../../th/guides/buying-checklist.md)
- [Українська](../../uk/guides/buying-checklist.md)
- [Tiếng Việt](../../vi/guides/buying-checklist.md)
- [Русский](../../ru/guides/buying-checklist.md)

## 1. 작업을 적고 네트워크를 고르십시오

출구가 해야 할 일을 적으십시오. 오래 유지되는 로그인, 특정 지역의 공개 데이터, 많은 요청, 모바일 통신사 시험 등입니다. 그것을 [프록시 유형 안내](./proxy-types.md)의 네트워크 유형, 즉 가정용, 데이터센터, ISP, 모바일에 맞추십시오. 홈페이지와 가격 페이지가 서로 다른 시작 가격이나 국가 수를 광고하면 둘 다 적고, 실제로 살 등급에는 어느 숫자가 적용되는지 물어보십시오.

## 2. 세션 동작을 확인하십시오

같은 출구가 몇 분, 몇 시간, 또는 임대 기간 내내 필요한지, 아니면 요청마다 새 출구가 필요한지 정하십시오. 스티키 또는 고정의 길이, 그것을 끊는 조건, 떨어진 IP가 교체되는지를 확인하십시오. 공식 문서가 유지 시간을 두 가지로 적는 경우가 있습니다. 사업자가 확인할 때까지는 정하지 않은 항목으로 두십시오.

## 3. 프로토콜과 인증을 확인하십시오

HTTPS 사이트에 쓰는 [HTTP CONNECT](https://proxyvendors.com/ko/glossary/http-connect)를 포함한 HTTP는 [SOCKS5](https://proxyvendors.com/ko/glossary/socks5)와 다릅니다. 가정용 제품 중에는 HTTP와 HTTPS만 지원하는 것이 있습니다. SOCKS5나 SOCKS5를 통한 UDP가 필요하면 제품과 클라이언트가 모두 지원하는지 확인하십시오. 진입 호스트, 포트, 인증 방법을 확인하십시오. 사용자 이름과 비밀번호, IP 허용 목록, 또는 둘 다입니다. CONNECT 중 407 응답은 프록시에서 옵니다. 이 상태는 Proxy Authentication Required를 뜻합니다. 프록시가 인증을 요구하거나, 받은 인증을 받아들이지 않은 것입니다. 터널은 만들어지지 않았고, 대상 사이트는 그 요청을 보지 못했습니다.

## 4. 실제 비용을 더하십시오

제목에 나온 단가만 보지 마십시오. 최소 구매량, 패키지 유효 기간, 초과 요금, 재시도로 낭비되는 양, 세밀한 지정에 붙는 추가 요금, 부가가치세, 자동 충전이나 자동 갱신을 적으십시오. 강조된 가격은 대량 구간의 가격일 수 있고, 처음 살 패키지의 가격이 아닐 수 있습니다. 시험에 카드가 필요하고 자동 충전이 켜진다면, 시작하기 전에 끌지 결정하십시오.

## 5. 시험, 환불, 이용 규칙을 읽으십시오

시험의 양과 기간, 환불 기간, 사용 한도, 환불에 문서화된 네트워크 장애가 필요한지 확인하십시오. 신원 또는 KYC 확인, 은행이나 정부 사이트처럼 막힌 범주, 고정 또는 전용 상품의 공정 사용 한도도 보십시오. 출처나 규정 준수가 중요하면 마케팅 문구에만 기대지 말고 사업자에게 문서를 요청하십시오.

## 6. 네트워크를 확인하고 시험하십시오

특정 통신사가 필요하면 [ASN 지정](https://proxyvendors.com/ko/glossary/asn)이 지원되는지, 쓸 수 있는 출구가 없을 때 무슨 일이 생기는지 확인하십시오. 그다음 작고 실제적인 작업을 실행하십시오. 대상이 유효한 응답을 주는지, 세션이 끊기는지, 위치가 정확한지, 실제로 쓴 트래픽은 얼마인지입니다. 연결한 뒤 [IP 확인](https://proxyvendors.com/ko/ip-check)으로 공인 IP, 기관, ASN을 구매한 제품과 비교하고, DNS와 WebRTC 경로가 중요하면 그 검사도 실행하십시오.

그 다음에 얼마나 살지 결정하십시오.

— Northleaf Studio
