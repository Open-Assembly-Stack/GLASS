# GLASS - Graphics Library in Assembly

## NOTICE: THIS LIBRARY IS STILL IN EARLY DEVELOPMENT. EXPECT LATE-TIME UPDATES AND COMMITS.

### Have you ever wanted to use your assembly brain to make an application with GUI? No? Yes? Maybe?
  It doesn't matter! GLASS is here for you to use! THough here are a few things to note:

# 1. It's Linux-exclusive
  This means no Windows, MacOS, DOS, (pure) Android support (or perhaps not **yet**)
  Until then, maybe there'll be some tools out there that translate GLASS-based applications into OpenGL, Vulkan, DirectX, or Metal calls

# 2. It's made with GNU Assembler (GAS)
  Which means cross-arch support, so Android is still kinda possible hence it's Linux-based iirc.
  And the library doesn't use `.intel_syntax prefix` so, abandon all hope, ye who modify or fork.

# 3. The library is in the same layer as Mesa so be careful trying to run it
  Mesa runs on KMS and DRM. GLASS does that as well, which may cause a conflict so do be careful.
  But I, OutOfIQ, would recommend using a TTY (TeleTypeWritter) to make it run as window support is yet to come.

# Community:
- (Discord)[https://dyno.gg/manage/1501565524448907314]
