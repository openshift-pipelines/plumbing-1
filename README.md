# Midstream CI

This branch hosts customizations for midstream CI of TekconCD Projects

## Generate Build Cop Rotation

run this command from `release-next` branch
```bash
go run ./main.go -start-date 2021-06-07 -days $((8 * 7)) -names nikhilthomas,kbaig,pgarg,chmouel,pradkuma,concaf,savita,shivam,vinjain,praveen_thangadancha,vdemeester,rupalib  > buildcaptain-rotation.csv
```

Ref: [generate-rotation docs](https://github.com/tektoncd/plumbing/tree/main/bots/buildcaptain/cmd/generate-rotation-csv#generate-rotation-csv)
