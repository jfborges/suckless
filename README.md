## Custom build of suckless tools (DWM, DMENU, SLOCK and ST with nord colors )

- DWM: dynamic window manager
- DMENU: dynamic menu for X
- SLOCK: Simple X display locker.
- ST: simple terminal

### tip! restart dwm without closing X 

• add the following to your .xinitrc ( bottom )
```
while true; do
		# Log stderror to a file
		dwm 2> ~/.dwm.log
		# No error logging
		#dwm >/dev/null 2>&1
done
```

---
20221007144457

! vanity gaps no applied this time.
