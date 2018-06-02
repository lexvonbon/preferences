# Repository Naming Conventions

### Build Output

**&lt;name&gt;.YYYYMMDD.bb[.hhmmss][.Ws]**

where &lt;name&gt; is the designated version name such as "Lipid" or "Carbo".  The
  date of release follows in the format of YYYYMMDD.  Next the patch number is
  given as a numeric [1-99].  Optionally, minor code corrections and working
  streams can be described in the given order.  Minor code corrections are
  denoted with the time in which they were merged [hhmmss].  Working streams
  are shown as single characters for either developer release (d), standard
  build (b), or bleeding edge alpha (a).

### Tags

**config.&lt;name&gt;**

where config is the independent component name (i.e. "System", "Input", or
  "Thread").  The &lt;name&gt; segment corresponds to the version name that the
  component runs on.
