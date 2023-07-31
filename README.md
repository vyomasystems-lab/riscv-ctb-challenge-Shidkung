# riscv_ctb_challenges
# Challenge Level1
Challenge_Level1_Logical:
-----------------------------------------------------
    and a2, s2, t5
	and a6, a2, s10
	and tp, s11, ra
	and s10, s0, tp
	and s3, a2, sp
	and a5, a6, t0
	and sp, a4, a1
	and t2, a4, z4
	and s9, a5, t0
	and s11, a1, a7
	and t3, s8, s0
in this challenge ,there is an error on Z4 because in assembly code in preparation zone
    
	# Preparation
	li s9, 0x06aa934a
	li a2, 0xbb90907f
	li s7, 0xbef962bf
	li t4, 0x585e49a1
	li a1, 0xcc22397b
	li s0, 0x7d9b8cb3
	li s5, 0x5e699bfd
	li a4, 0x26d0e5ad
	li s1, 0x09610f5a
	li s2, 0xc9b5593a
	li t5, 0xe920afcd
	li s10, 0x1748702ab
	li s11, 0x69f94c6ba
	li sp, 0x89883f62
	li t0, 0xba4da205
	li s4, 0xff5df24
	li a7, 0x9623de9
	li s8, 0xd2f5ee1
	li t1, 0x9ed6fb57
	li a3, 0xfec194e4

There not have "z4" but it have "s4" So I fix it by change all "z4" to "s4"


