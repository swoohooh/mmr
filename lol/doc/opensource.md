Opensource

# lol-replay

## record/record.go
지역이 나누어져 있는데 지역이 통합되서 필요 없을듯?
gameID 가 필요하다. 어떻게 찾지?

### thisRecorder.waitForFirstChunk
왜 메타로 비교하지?

### thisRecorder.recordFrames
recording.ChunkInfo 가 frame 인가?


## record/retrieve.go
각종 api를 확인 가능
api중에 frame 번호를 보내면 결과를 가져오는게 있는데 리턴값이 뭐지? hls 프로토콜인가?


## recording/retrieve.go
gob 조사 필요


## replay/replay.go
"application/octet-stream" ???

이 코드에 라우터 존재


## server/monitor.go
사용자 모니터와 게임 기록 기능이 존재



# Unofficial API
- https://github.com/EloGank/lol-replay-observer/blob/master/docs/usage.md
- https://gist.github.com/Aztorius/e428be6515b19fd24823754b72038e1b
- https://gamedev.stackexchange.com/questions/49856/league-of-legends-spectator-stream-format
- https://github.com/robertabcd/lol-ob
- https://gist.github.com/anonymous/5067051
- https://qastack.kr/gamedev/49856/league-of-legends-spectator-stream-format
