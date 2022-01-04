# FatalExecutionEngineError

This is a default ASP.Net MVC application created using VS 2019. 
It targets .Net Framework 4.7.2

Upon debugging in VS, it tries to run the app in IISExpress process but fails with error:

Managed Debugging Assistant 'FatalExecutionEngineError' 
  Message=Managed Debugging Assistant 'FatalExecutionEngineError' : 'The runtime has encountered a fatal error. The address of the error was at 0x72605de7, on thread 0x88c4. 
  The error code is 0xc0000005. This error may be a bug in the CLR or in the unsafe or non-verifiable portions of user code. 
  Common sources of this bug include user marshaling errors for COM-interop or PInvoke, which may corrupt the stack.'
  
Similar problem has also been reported in stackoverflow: 
https://stackoverflow.com/questions/70169631/managed-debugging-assistant-fatalexecutionengineerror-error-in-iis-express

