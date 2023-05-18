# SYC - Simple Yet Complex
Library/framework for TwinCAT with aim to provide highly automated sequencer and symbol monitoring.

Now kind of abandoned like rest of my repos. But you may find some useful code inside anyway.


### Regex
- supports `^$.*+`
- `fbRegex.match(pattern := 'he.+o', text := 'hellllo').found = TRUE`
- converted with poor performance from some C implementation on interwebs
### Time provider
- get time in your own format easily
- `tp.GetTimeString({h}:{mm} whatever {ss}) = '6:05 whatever 33'`

### SymbolProvider_1
- methods to retrieve variable name and datatype
- takes time to execute, but is synchronous
- works just by passing variable into method, it is executed during runtime (not while compilation like __VARINFO)