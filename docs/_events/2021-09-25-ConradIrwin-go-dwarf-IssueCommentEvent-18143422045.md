---
event_type: IssueCommentEvent
avatar: "https://avatars.githubusercontent.com/u/814322?"
user: vsoch
date: 2021-09-25
repo_name: ConradIrwin/go-dwarf
html_url: https://github.com/ConradIrwin/go-dwarf/issues/1
repo_url: https://github.com/ConradIrwin/go-dwarf
---

<a href='https://github.com/vsoch' target='_blank'>vsoch</a> commented on issue <a href='https://github.com/ConradIrwin/go-dwarf/issues/1' target='_blank'>ConradIrwin/go-dwarf#1</a>.

<small>Wow I didn't realize it dated back to 2014, that's so awesome! I'm definitely more new to go and DWARF, and am really loving working in this niche space. I'm definitely going to look over your work here carefully - I think my use case is different but I would want to know the same information to extract metadata about libraries to assess ABI. I did a bunch of work this evening on [the library I'm working on](https://github.com/vsoch/go-smeagle) that lets me parse the dwarf (using debug/dwarf included with my project to get access to private functions) and I'm at the point where I have a basic set of functions and global variables, and I think I'm going to need to tweak [ReadType](https://github.com/vsoch/go-smeagle/blob/c8def068d4adb96947af03be9d43fcfb64bf9234/pkg/debug/dwarf/type.go#L299) to be able to get the original Types (e.g., dwarf.FuncType instead of a general dwarf.Type) because I'll need to know the underlying types / specific class beyond the DIE tag to  be able to reproduce what the [System V ABI](https://raw.githubusercontent.com/dyninst/ABI-Analysis-for-Dynamic-Calls/master/callsite_parsing/docs/AMD64/x86-64-psABI-1.0.pdf) says in terms of mapping things to registers. Or even before that, I'm just trying to figure out how to clearly mark something as a pointer, with N redirections, to an underlying type Y....</small>

<a href='https://github.com/ConradIrwin/go-dwarf/issues/1' target='_blank'>View Comment</a>