# socgen_BusDefs
Bus and abstraction definitions for socgen

Bus name collisions are prevented by assign a unique Bus ID string to each bus.
The bus name will consist of the bus identifier followed by the submember name
from the abstractionDefinition.

If a module has multiple busses of the same type then this may be preceeded by an
adhoc descriptor.


Bus Name      Bus ID
------------------------------------------------------------
clock          clk
enable         enable
reset          reset
irq            irq
pads           pad
ahb            ahb
axi            axi
ext_bus        eb
micro_bus      mb
wishbone       wb
sram           sram