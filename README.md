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