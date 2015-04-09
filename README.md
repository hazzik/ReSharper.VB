# ReSharper.VB
A set of SSR for VB.NET

Supported SSR
-------------

* `$x$ Is Nothing OrElse $x$ = ""` => `String.IsNullOrEmpty($x$)`
* Convert If-Then-Else to conditional
* `IsNothing($x$)` => `$x$ Is Nothing`
* Replace `IIf` with `If` operator
* Simplify conditional operator (`If($x$ Is Nothing, $y$, $x$)` => `If($x$, $y$)`)
