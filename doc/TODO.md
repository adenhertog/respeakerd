- [x] python client: add reconnect mechanism
- [x] fix pixel_ring light error when it's interrupted by wakeup event during speaking
- [x] add  on_ready event reporting for the success of connecting AVS, respeakerd should use this event to pause voice commands until get on_ready.
- [x] add command line options for the parameters of respeakerd, using gflags.
- [x] PulseAudio mode, support PulseAudio pipe-source module
