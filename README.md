Download Link: https://assignmentchef.com/product/solved-ece5484-homework5
<br>
<ol>

 <li>Suppose a computer using direct mapped cache has 2<sup>64 </sup>bytes of byte-addressable main memory, and a cache of 2048 blocks, where each cache block contains 64 bytes.

  <ol>

   <li>How many blocks of main memory are there?</li>

   <li>What is the format of a memory address as seen by the cache, i.e., what are the sizes of the tag, block, and offset fields?</li>

   <li>To which cache block will the memory address 0x00000000000163FA map?</li>

  </ol></li>

 <li>Suppose a computer using fully associative cache has 2<sup>24 </sup>bytes of byte-addressable main memory and a cache of 128 blocks, where each cache block contains 64 bytes.

  <ol>

   <li>How many blocks of main memory are there?</li>

   <li>What is the format of a memory address as seen by the cache, i.e., what are the sizes of the tag and offset fields?</li>

   <li>To which cache block can the memory address 0x01D872 map?</li>

  </ol></li>

 <li>Suppose a byte-addressable computer using set associative cache has 2<sup>21 </sup>byes of main memory and a</li>

</ol>

cache of 64 blocks, where each cache block contains 4 bytes.

<ol>

 <li>If this cache is 2-way set associative, what is the format of a memory address as seen by the cache, that is, what are the sizes of the tag, set, and offset fields?</li>

 <li>If this cache is 4-way set associative, what is the format of a memory address as seen by the cache?</li>

</ol>

<ol start="4">

 <li>Suppose we have 2<sup>20 </sup>bytes of virtual memory, 2<sup>16 </sup>bytes of physical main memory and the page size is 2<sup>8 </sup>

  <ol>

   <li>How many pages are there in virtual memory?</li>

  </ol></li>

</ol>

<ol>

 <li>How many page frames are there in main memory?</li>

 <li>How many entries are in the page table for a process that uses all of virtual memory?</li>

</ol>

<ol start="5">

 <li>For the system in problem 4, suppose a main memory access requires 30ns, the page fault rate is .01%, it costs 12ms to access a page not in memory (this time includes the time necessary to transfer the page into memory, update the page table, and access the data). Also suppose a TLB hit requires 7ns, the cache miss rate is 3%, the TLB hit rate is 95%, a cache hit requires 15 ns. On a TLB or cache miss, the time required for access includes a TLB and/or cache update, but the access is not restarted. On a page fault, the page is fetched from disk, all updates are performed but the access is restarted. All references are sequential (no overlap, nothing done in parallel)

  <ol>

   <li>Calculate the time for a TLB hit and a cache hit.</li>

   <li>Calculate the EAT (effective access time) for a TLB hit.</li>

  </ol></li>

 <li>A system implements a paged virtual address space for each process using a one-level page table. The maximum size of virtual address space is 32MB. The page table for the running process includes the following valid entries (the → notation indicates that a virtual page maps to the given page frame, that is, it is located in that frame):</li>

</ol>

Virtual page 3 → page frame 6

Virtual page 5 → page frame 10

Virtual page 8 → page frame 5

Virtual page 4 → page frame 2

Virtual page 0 → page frame 1

The page size is 2048 bytes and the maximum physical memory size of machine is 4MB.

<ol>

 <li>How many bits are required for each virtual address?</li>

 <li>How many bits are required for each physical address?</li>

 <li>What is the maximum number of entries in a page table?</li>

 <li>To which physical address will the virtual address 0x37F translate?</li>

 <li>Which virtual address will translate to physical address 0x1203?</li>

</ol>