# VTOL VR 한국어 재번역 용어집

## 번역 원칙
1. **대상 독자**: 밀리터리 비전문가 한국 게이머. 무기 이름 포함 최대한 한국어로 옮기되, 실기체 명칭(AIM-120, GBU-38, Mk.82 등 형식번호)은 그대로 둔다.
2. **HUD/MFD 대문자 라벨**: 화면 폭이 좁으므로 짧고 명확하게. 널리 쓰이는 약어(GPS, IR, ECM, ILS, TWS, STT 등)는 영문 유지하되 설명문에서 첫 등장 시 풀어쓴다.
3. **설명문(description)**: "~입니다" 체 통일. 조사 앞 띄어쓰기 오류("미사일 입니다" → "미사일입니다") 수정.
4. **버튼/스위치 라벨**: 명사형 종결. 원문 길이와 비슷하게(UI 잘림 방지). 셀 안 줄바꿈은 유지.
5. **형식 보존**: Key/Description/en 열 수정 금지. `{0}` 등 플레이스홀더 보존. UTF-8 BOM + LF 유지.

## 핵심 용어 대역표

### 무장 일반
| 원문 | 번역 | 비고 |
|---|---|---|
| missile | 미사일 | |
| radar guided | 레이더 유도 | |
| IR / heat-seeking | 적외선 (유도) | "열추적"도 설명문에서 허용 |
| air-to-air missile (AAM) | 공대공 미사일 | HUD: 공대공 |
| air-to-ground | 공대지 | |
| surface-to-air (SAM) | 지대공 (미사일) | |
| anti-ship cruise missile | 대함 순항 미사일 | |
| anti-radiation missile (ARM) | 대레이더 미사일 | ❌ 반방사 |
| guided bomb | 유도 폭탄 | |
| dumb (bomb/mode) | 무유도 | |
| cluster bomb | 확산탄 | |
| rocket (pod) | 로켓 (포드) | |
| gun / cannon | 기관포 | ❌ 총 |
| terminal guidance/mode | 종말 유도 (모드) | ❌ 종점 기동 |
| SeaSkim | 해면 밀착 비행 | 시스키밍 |
| Popup | 급상승 공격 | 팝업 기동 |
| Direct | 직접 공격 | |
| standoff | 원거리 발사 | |
| booster | 부스터 | |
| warhead | 탄두 | |
| proximity fuse | 근접 신관 | |
| hardpoint | 무장 장착대 | ❌ 하드포인트 (비전문가 대상) |
| loadout | 무장 구성 | |
| salvo | 일제 발사 | |
| ripple | 연속 투하/발사 | |
| release | 투하 | 폭탄 |
| launch / fire | 발사 | |
| uncage | 시커 잠금 해제 | IR 미사일 시커 |
| seeker | 시커(탐색기) | HUD: 시커 |
| lock / lock-on | 록온 / 조준 고정 | 문맥에 따라 |

### 센서·전자전
| 원문 | 번역 | 비고 |
|---|---|---|
| radar | 레이더 | |
| RWR (radar warning receiver) | 레이더 경보 수신기 | HUD: RWR |
| TWS | TWS(추적 중 탐색) | HUD는 TWS 유지 |
| STT | STT(단일 목표 추적) | HUD는 STT 유지 |
| ACM (aerial combat maneuver mode) | 근접전 모드 | 레이더 모드일 때 |
| chaff | 채프 | ❌ 체프. "ECM Chaff" → 채프(레이더 교란) |
| flare | 플레어 | "IR Flares" → 플레어(적외선 기만) |
| countermeasures | 기만체 | 유지 |
| ECM / jammer / jamming | 전파 방해(ECM) / 재머 / 전파 방해 | |
| IFF | 피아식별(IFF) | |
| TGP (targeting pod) | 조준 포드 | |
| FLIR | 열영상(FLIR) | |
| laser designator | 레이저 조사기 | |
| track / tracking | 추적 | |
| acquisition / acquire | (목표) 포착 | ❌ 획득 |
| detect | 탐지 | |
| GPS | GPS | |
| datalink | 데이터링크 | |
| waypoint | 경유지 | 기존 번역 유지, 일관 적용 |
| target point | 목표 지점 | ❌ 원점 |
| PATH | 경로 | |
| POINT | 지점 | ❌ 원점 |
| IN/OVER RANGE | 사거리 내 / 사거리 초과 | ❌ 사정거리(통일: 사거리) |

### 비행·조종
| 원문 | 번역 | 비고 |
|---|---|---|
| throttle | 스로틀 | |
| joystick / stick | 조종간 | ❌ 조이스틱 (실기 용어) |
| rudder | 러더(방향타) | |
| flaps | 플랩 | |
| trim | 트림 | |
| AoA (angle of attack) | 받음각 | |
| pitch / roll / yaw | 피치 / 롤 / 요 | |
| heading | 기수 방위 | HUD: 방위 |
| altitude | 고도 | |
| airspeed | 대기속도 | HUD: 속도 |
| VTOL | 수직이착륙 | |
| hover | 호버링(제자리 비행) | |
| tilt (rotors/engines) | 틸트(엔진 각도) | |
| afterburner | 애프터버너 | |
| stall | 실속 | |
| g-force / G | 중력가속도(G) | HUD: G |
| landing gear | 착륙 장치(랜딩 기어) | HUD: 기어 |
| tailhook / hook | 착함 후크 | HUD: 후크 |
| catapult | 캐터펄트(사출기) | |
| arresting cable | 착함 제동 케이블 | |
| eject | 비상 탈출 | ❌ 긴급 탈출 (군 표준: 비상 탈출) |
| autopilot (A/P) | 자동 조종 | |
| nav mode | 항법 모드 | |
| ILS | 착륙 유도장치(ILS) | HUD: ILS |
| glideslope | 활공 경로 | |
| localizer | 방위 유도 | |
| fuel dump | 연료 방출 | |
| refuel(ing) port/probe | 공중급유구 / 급유 프로브 | |
| bingo (fuel) | 귀환 한계 연료 | |
| brake | 브레이크 | |
| parking brake | 주차 브레이크 | |

### 조종석·계기
| 원문 | 번역 | 비고 |
|---|---|---|
| cockpit | 조종석 | |
| canopy | 캐노피 | |
| instrument | 계기(판) | |
| MFD | 다기능 표시장치(MFD) | HUD: MFD |
| HUD | HUD | |
| HMCS / helmet | 헬멧 조준기 | |
| visor | 바이저 | |
| NVG | 야간투시경 | 붙여쓰기 |
| navigation lights | 항법등 | ❌ 탐색등 조명 |
| strobe lights | 충돌 방지등(스트로브) | ❌ 섬광등 |
| landing lights | 착륙등 | ❌ 착륙 조명 |
| cockpit lights | 조종석 조명 | |
| bay lights | 격실 조명 | ❌ 좌석 조명 (AV-42C 뒷칸) |
| instrument brightness | 계기 밝기 | |
| master arm | 무장 안전 스위치(마스터 암) | HUD: 마스터 암 |
| master caution | 주 경고등 | |
| warning / caution | 경고 / 주의 | |
| battery | 배터리 | |
| APU | 보조 동력장치(APU) | |
| avionics | 항전 장비 | |
| switch cover | 스위치 커버 | |
| knob | 노브 | 다이얼 허용 |
| toggle | 전환 | "~ 토글" 지양 |

### UI·미션
| 원문 | 번역 | 비고 |
|---|---|---|
| mission | 임무 | ❌ 미션 (통일) |
| campaign | 캠페인 | |
| briefing | 브리핑 | |
| objective | 목표 | |
| debrief | 결과 보고 | |
| ready room | 대기실 | |
| loadout/vehicle configuration | 무장 설정 | |
| budget | 예산 | |
| flight cost | 출격 비용 | |
| repair | 수리 | |
| rearm / reload | 재무장 | "재무장중" → "재무장 중" |
| quicksave / quickload | 빠른 저장 / 빠른 불러오기 | |
| workshop | 창작마당 | Steam 공식 명칭 |
| multiplayer | 멀티플레이 | |
| allied / friendly | 아군 | |
| enemy / hostile | 적군 / 적 | |
| carrier | 항공모함 | |
| airbase | 공군기지 | |
| spawn | 배치 | ❌ 스폰 |

## 자주 나온 오역 수정 목록 (발견 즉시 추가)
- 종점 기동 → 종말 유도
- 원점(POINT) → 지점
- 탐색등 → 항법등
- 좌석 조명(Bay Lights) → 격실 조명
- 섬광등 → 충돌 방지등
- 체프 → 채프
- 사정거리 → 사거리
- 조이스틱 → 조종간
- 긴급 탈출 → 비상 탈출
- 목표 획득 → 목표 포착
- "~ 입니다" 띄어쓰기 → "~입니다"
- 미션/임무 혼용 → 임무
