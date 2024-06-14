package cxosenv

import (
  "syscall"
)

func SetPriority(priority int) error {
	pid := syscall.Getpid()
	err := syscall.Setpriority(syscall.PRIO_PROCESS, pid, priority)
	return err
}
