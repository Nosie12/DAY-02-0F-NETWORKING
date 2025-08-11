# 🖥️ Understanding Binary to Decimal Conversion for IP Addresses

## 📌 Summary
This guide explains how to convert an IP address from **binary notation** to **decimal notation** step-by-step. IP addresses are made up of four **octets**, each containing 8 bits (1s and 0s). Each bit represents a specific value based on its position in the octet.

---

## 🔍 Step-by-Step Conversion Process

### 1️⃣ Know the Binary Table for an Octet
Each position in the octet has a fixed decimal value:

| Bit Position      | Decimal Value |
|-------------------|---------------|
| 1st (leftmost)    | 128           |
| 2nd               | 64            |
| 3rd               | 32            |
| 4th               | 16            |
| 5th               | 8             |
| 6th               | 4             |
| 7th               | 2             |
| 8th (rightmost)   | 1             |

---

### 2️⃣ Example Conversion
Let’s say we have the following binary IP address:

`11000000.10101000.11111110.00000001`

We will convert each octet **separately**.

---

#### First Octet: `11000000`
- 1st bit (128) ✅ ON → 128  
- 2nd bit (64) ✅ ON → 64  
- Remaining bits are 0 ❌ OFF → 0  

**Calculation:** 128 + 64 = **192**

---

#### Second Octet: `10101000`
- 1st bit (128) ✅ ON → 128  
- 3rd bit (32) ✅ ON → 32  
- 5th bit (8) ✅ ON → 8  
- Others are 0 ❌ OFF → 0  

**Calculation:** 128 + 32 + 8 = **168**

---

#### Third Octet: `11111110`
- All bits ON except the last one (1)  
- 128 + 64 + 32 + 16 + 8 + 4 + 2 = **254**

---

#### Fourth Octet: `00000001`
- Only last bit ON → 1  

**Calculation:** **1**

---

### 3️⃣ Final Decimal Representation
Putting it all together:

**Binary:** `11000000.10101000.11111110.00000001`  
**Decimal:** **192.168.254.1**

---

## 💡 Key Takeaways
- Each octet contains **8 bits**, and each bit corresponds to a specific decimal value.
- To convert binary to decimal, **add up the values** of the bits that are set to **1**.
- Repeat this process for all four octets to get the final IP address in decimal form.

---
