# containers
my container images


resize imgs:

```bash
ls ./*.png -1 | xargs -I'{}' ggwm -f "./{}" -t "./out/{}" -r 2 -w 1080
```
