# Packet switching
> The host breaks application-layer messages into [[packet | packets]]

## Store and forward
![[Pasted image 20220927162834.png]]

### End-end delay
$$\frac{2 \cdot \text{Dimensione pacchetto}}{\text{Velocità di trasmissione}}$$

### Packet queuing and loss
![[Pasted image 20220927163633.png]]
> If arrival rate (in bps) to link exceeds transmission rate (bps) of link for a period of time
> - packets will queue, waiting to be transmitted on output link
> - packets can be dropped (lost) if memory (buffer) in router fills up

---
#reti 2022-09-27