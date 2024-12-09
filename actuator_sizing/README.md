# Sorry, I did not use lxml
# I calculated armatures myself and pasted to xml files by hand :)


### Example Calculation for the Shoulder Lift Joint (CRA-RI80-110-PRO-XX)

1. **Reflected Inertia**:
   $$
   I_{\text{reflected}} = 0.00015 \times 80^2 = 0.96 \, \text{kg*m}^2
   $$

2. **Steiner's Contribution**:
   $$
   I_{\text{new}} = 0.96 + 1.5 \times (0.12)^2 = 0.96 + 0.0216 = 0.9816 \, \text{kg $\cdot$ m}^2
   $$

3. **Armature**:
   $$
   \text{armature} = \frac{I_{\text{new}}}{\text{link mass}} = \frac{0.9816}{2.0} = 0.4908
   $$

---

### Example Calculation for the Shoulder Pan Joint (CRA-RI70-90-PRO-XX)

1. **Reflected Inertia**:
   $$
   I_{\text{reflected}} = 0.00012 \times 100^2 = 1.2 \, \text{kg $\cdot$ m}^2
   $$

2. **Steiner's Contribution**:
   $$
   I_{\text{new}} = 1.2 + 1.2 \times (0.15)^2 = 1.2 + 0.027 = 1.227 \, \text{kg $\cdot$ m}^2
   $$

3. **Armature**:
   $$
   \text{armature} = \frac{I_{\text{new}}}{\text{link mass}} = \frac{1.227}{2.0} = 0.6135
   $$
