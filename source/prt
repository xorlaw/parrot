#!/usr/bin/env bash

# Parrot - a bird in your terminal!
# If you are new here, read the About page to know what Parrot actually is.


# Exit if no command was given to Parrot.
if [ "$1" = "" ]; then
		echo "[*] You must give me something to echo!"
		echo "[*] Usage: prt <cmd>"
		exit 1
fi


# Reconstruct command passed to Parrot
CMD="$*"


# Output command to user, ask if they want to execute command 
echo "[*] Squawk! Parrot heard:"
echo " $CMD"
echo 
read -rp "[*] Are you sure you want to run this command? [y/n] :" CONFIRM

case "$CONFIRM" in 
		y|Y|yes|YES|mhm|sure)
				echo "[*] Executing.."
				exec "$@"
				;;
		*)
				echo "[*] Aborted command."
				exit 0
				;;
esac
