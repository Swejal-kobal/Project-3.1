Bit:

RAM64:
![image](https://github.com/user-attachments/assets/18a0e5ad-28be-4b3a-9043-c5cfbbe48a35)
 CHIP RAM64 {

    IN in[16], load, address[6];
    OUT out[16];

    BUILTIN RAM64;
    CLOCKED in, load;

RAM8:
![image](https://github.com/user-attachments/assets/84aa4a6e-b4ff-44c6-aada-0d59522b5bc8)
 CHIP RAM8 {

    IN  in[16], load, address[3];
    OUT out[16];

    BUILTIN RAM8;
    CLOCKED in, load;
}

Register:

