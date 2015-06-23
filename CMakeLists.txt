project(moonlight)

set(MOONLIGHT_SOURCES
limelight-common/AudioStream.c
limelight-common/ByteBuffer.c
limelight-common/Connection.c
limelight-common/ControlStream.c
limelight-common/FakeCallbacks.c
limelight-common/InputStream.c
limelight-common/LinkedBlockingQueue.c
limelight-common/PlatformSockets.c
limelight-common/PlatformThreads.c
limelight-common/RtspConnection.c
limelight-common/RtspParser.c
limelight-common/SdpGenerator.c
limelight-common/VideoDepacketizer.c
limelight-common/VideoStream.c
limelight-common/OpenAES/oaes_base64.c
limelight-common/OpenAES/oaes_lib.c
)

add_library(moonlight SHARED ${MOONLIGHT_SOURCES})