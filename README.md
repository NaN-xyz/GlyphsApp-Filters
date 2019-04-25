# GlyphsApp Filters

Hopefully more to come.

## Angularizzle.py

Takes lovingly crafted glyphs and disfigures their curves by sharp line. Visually it has something akin to Illustrator's "Simplify" but is more nuanced (imvfho). The 'Keep detail' option attempts to protect the form's integrity. Unselected it's allowed to devolve down to brutish polygon. Only works with cubic curves so if you import TTFs be sure to convert.

Can be used on a glyph-by-glyph basis or across the entire selected font.

Custom parameters can be set to filter on the instance export rather than editing the font directly. Sample:

```
Angularize; segsize:120; detail:True;
```

## License

Copyright 2019 [Luke Prowse](http://twitter.com/luke_prowse). Licensed under the Apache License, Version 2.0 (the "License"); you may not use the software provided here except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

See the License file included in this repository for further details.
