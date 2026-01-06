# First In First Out (FIFO) is a very popular and useful design block for purpose of synchronization and a handshaking mechanism between the modules.

**Depth of FIFO**: The number of slots or rows in FIFO is called the depth of the FIFO.

**Width of FIFO**: The number of bits that can be stored in each slot or row is called the width of the FIFO.



### In Synchronous FIFO, data read and write operations use the same clock frequency. Usually, they are used with high clock frequency to support high-speed systems.

## synchronous fifo

FIFO write operation
FIFO can store/write the wr_data at every posedge of the clock based on wr_en signal till it is full. The write pointer gets incremented on every data write in FIFO memory.

FIFO read operation
The data can be taken out or read from FIFO at every posedge of the clock based on the rd_en signal till it is empty. The read pointer gets incremented on every data read from FIFO memory.

## elaborated design 
<img width="1312" height="724" alt="image" src="https://github.com/user-attachments/assets/bd2b937b-9061-4b8c-a379-bb80f6729a87" />

### output
<img width="1564" height="381" alt="image" src="https://github.com/user-attachments/assets/a3d72450-3d57-48bd-81bf-0aa43bca5772" />
