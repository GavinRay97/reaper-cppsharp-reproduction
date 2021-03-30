```sh-session
$ "./Release_x64/CppSharp.CLI.exe" -o ./reaper-generated --debug --verbose \
  --generator=cli --platform=win --arch=x64 \
  --exceptions --rtti --checksymbols \
  -D=REAPERAPI_IMPLEMENT \
  ./include/reaper_plugin_functions.h
```
