cpp-call-csharp
===============
- https://www.codeproject.com/Tips/695387/Calling-Csharp-NET-methods-from-unmanaged-C-Cplusp

### The Idea
- C# code exported functions referenced by Managed C++ dll
- Managed C++ dll reexports these C# exported functions as Unmanaged C `__declspec(dllexport)`
