[RAW Bytes]
.]F_&21 20881BG5HHP-RPT 010010.
500000HHPLINK         999          HHPLINK SERVER.563306CN 63306     001          BM-TG46001    .518829CN CC#1       001          TG 460501     .580337CN CHINA #1     033          W24166/TG46001.582442CN CHINA #2     007          W24269/TG46072.563305CN-C4P25-46005  500          YSF2P25-BM4600.563303CN-C4P25-46851  001          CROSS-BM460851.540973CN-CHINA-03     004          C4FM          .510000LOCALTEST#1    001          TG 460501     .50001ZZ PARROT     000          PARROT        . ...

[SEQ]
m_seqNo

[ALL_RESP Cmd Type]
0x5D, 0x46, 0x5F, 0x26

[ALL_RESP Data Type]
'2', '1'

[ALL_RESP Record Head]
7:5:    m_id
12:10:  m_node
22:5:   010010 : current_list_len(max 20), total_len(max 999))

[ALL_RESP Record Entries]

Total = 50 bytes for each
0:1:    '5'
1:5:    m_id
6:16:   m_name
22:3:   m_count
25:10:  ' '
35:14:  m_desc
49:1:   0x0D

...
repeat 50, in 1000 bytes total
...

[ALL_RESP Record Tail]
0x03
CRC8(of above data)


