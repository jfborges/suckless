# Custom build of suckless tools such as DWM and ST ( nord colors )

- DWM: dynamic window manager
- ST: simple terminal

## dwm Window Manager - ( restart dwm without closing X )

• add the following to your.xinitrc ( bottom )
```
while true; do
		# Log stderror to a file
		dwm 2> ~/.dwm.log
		# No error logging
		#dwm >/dev/null 2>&1
done
```

---
20220408151708
