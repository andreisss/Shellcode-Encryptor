# Shellcode-Encryptor

/*	ADVANCED SHELLCODE RUNNER
-------------------------------------------
	Does sandbox evasion and behavioural anomalies to bypass AV engines. 
	------------------------------------------------------------------------
	Decrypts XOR encrypted shellcode and injects it into the current process.
  --------------------------------------------------------------------------
  */
/*
key win32 API calls:
  - kernel32.dll:
    1: 'VirtualAlloc'
    2: 'CreateThread'
    3: 'WaitForSingleObject (WAIT_FAILED)'
*/
