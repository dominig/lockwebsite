# lockwebsite
Simple script to look a the directory of a website

Lock or unlock a web site 
by remowing write access to owner and group

Usage: lockwebsite [-v] websitedir lock|unlock
       -v: Verbose debug
       websitedir: Path to the directory containing the site
       lock:    Lock the site by removing all write access
       unlock:  Ulock the iste by reactivating write access
ex:
   sudo lockwebsite.sh MyWebSiteDir lock
