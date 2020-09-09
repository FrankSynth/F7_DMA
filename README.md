# F7_DMA

```
SECTIONS
{
    .dma_buffer : /* Space before ':' is critical */
    {
    *(.dma_buffer)
    } >RAM
}
```

Das ist beim F7 nicht unbedingt notwendig, da im Gegensatz zum H7 der Flash ebenfalls an DMA angebunden ist. Allerdings hat der flash nur wenige write cycles (10k), weswegen unbedingt fuer DMA der Ram verwendet werden sollte.

## Clocks
Max Clockings koennen aus diesem Projekt bezogen werden.