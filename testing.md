###Unity Testing notes

##Testing Style
Tests should use the "constraint based testing" style.

Prefer <code>Assert.That(1, Is.EqualTo(1));</code> to <code>Assert.AreEqual (1, 1);</code>

Info on the constraint style available [here](https://github.com/lukewickstead/DOT-NET-on-Linux/blob/master/CheatSheets/NUnitCheatSheet.cs).
