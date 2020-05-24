# Investigating a challenge of building a superconducting quantum computer

## Second title

Probing two-level systems with a surface acoustic wave resonator

## Authors

- Nuttamas Tubsrinuan (\*)
- Gustav Andersson
- Per Delsing

(\*) corresponding author: nuttamas@student.chalmers.se

## About the authors

Ms. Nuttamas Tubsrinuan is an Erasmus Mundus Master of Nanoscience and Nanotechnology, specializing in quantum computing. She is studying in the joint-degree program between KU Leuven, Belgium and Chalmers University of Technology, Sweden. This work is conducted under supervision of Gustav Andersson and professor Per Delsing at the Quantum Technology laboratory (QT), Chalmers University of Technology and the Wallenberg Center for Quantum Technology (WACQT), Sweden.

## Acknowledgments

NT acknowledge the European Commission for the Erasmus Mundus scholarship and Chalmers University of Technology and WACQT for the laboratory facilities.

## Keywords

superconducting quantum computer, quantum circuit, two-level system, surface acoustic wave resonator, resonance frequency fluctuations

## Highlight text

Parasitic two-level systems (TLS) coupling to a superconducting quantum circuit causes information loss. To mitigate this problem, better physical understanding of the coupling mechanism is crucial. We investigate noise causes by TLS interaction using a surface acoustic wave resonator. The results show a significant correlation of resonance frequency fluctuations between different resonance modes, supporting the prediction of the TLS model.

## Figure

(Top left) schematic of measurement setup, (right) a dilution refrigerator that hosts a SAW resonator, and (bottom left) resonance frequency fluctuations calculated from three different modes of a SAW resonator, showing similar features.

## Abstract

### Background

Quantum computing shows high potential to overcome computational limit of classical computers and offer computational power beyond current state-of-the-art technology. To implement the concept of quantum computing, a reliable fundamental unit of information, the quantum bit (qubit), must be achieved. One of the proposed candidates for qubit that is promising for the transfer from research field towards real applications is the superconducting qubit. Despite having the advantages of scalability and compatibility with existing microwave control systems, the energy loss in a quantum circuit due to the coupling with parasitic two-level system (TLS) defects remains unsolved. 
TLSs can be classified as coherent TLS and incoherent TLS. Previous studies, e.g. Burnett et al. (2014), and Müller et al. (2015), showed that coherent TLSs directly couple with a quantum circuit. Meanwhile, incoherent TLSs interact with coherent TLSs, bringing the coherent TLSs in and out resonance with our system. This effect results in resonance frequency fluctuations. The conventional approach of monitoring TLS interaction is to measure phase noise in either a superconducting qubit or a microwave resonator. However, those devices only allow the study of TLS interaction at one specific resonance frequency.

### Method

In this work, we employ a surface acoustic wave (SAW) resonator as a tool for probing TLSs. Since acoustic wave has much lower velocity than electromagnetic wave, A SAW resonator can accommodate many resonance modes in a limited chip size. This permits the study of interaction between TLSs in different modes, rather than only one mode as a microwave resonator can do. 
A SAW resonator is mounted in a dilution refrigerator, keeping the temperature approximately at 10 millikelvin. A multi-frequency lock-in amplifier connected with an I-Q mixer generates high frequency signals corresponding to SAW resonator frequencies simultaneously. The reflected signals from the resonator contains phase noise, which is the effect of TLS coupling. Phase noise data are used to calculate resonance frequency fluctuations for each mode. Then, correlation of the resonance frequency fluctuations between different modes are determined.
A script for measurement is written in python. A CircleFit notebook (Probst et al., 2015) is utilized for fitting resonator parameters. Finally, data analysis is performed using Matlab and python.

### Result
The preliminary result indicates relationship of frequency fluctuation among different modes of a SAW resonator. Further analysis reveals significant correlation coefficients and indicates that the correlation of resonance frequency fluctuations decreases with increasing detuning. In addition, the degree of correlation shows power dependence, which remains to be investigated.

### Discussion and conclusion

This work experimentally demonstrates that phase noise in different modes is correlated, providing the evidence of interaction between incoherent TLSs and coherent TLSs as the cause of this phenomenon.

### References

Müller, C., Lisenfeld, J., Shnirman, A, and Poletto, S. 2015. “Interacting two-level defects as sources 
of fluctuating high frequency noise in superconducting circuits”. Physical Review B, 92(3): 305442.
Burnett J., Faoro, L., Wisby, I. Gurtovio, V.L., Chernykh, A.V., Mikhailoz, G.M., Tulin, V.A., 
Shailhaidarov,  R., Antonov, V., Meeson, O.J., Tzalenchuk, A.Y. and Linström, T. 2014. 
“Evidence for interacting two-level systems for the 1/f noise of a superconducting 
resonator”. Nature Communication (5): 4119.
Probst, S., Song, S.B., Pushen, P.A., Ustinov, A.V., and Weides, M. 2015. “Efficient and robust analysis    of complex scattering data under noise in microwave resonators”. Review of Scientific       Instrument (86): 024706.

# การศึกษาอันตรกิริยาระหว่างระบบสองสถานะในวงจรควอนตัมแบบสภาพยวดยิ่ง

## โดย
- ณัฐมาศ ทับศรีนวล 
- Gustav Andersson
- Per Delsing (\*)

(\*) ผู้รับผิดชอบหลัก nuttamas@student.chalmers.se

## ประวัตินักวิจัย
นางสาวณัฐมาศ ทับศรีนวล เป็นนักเรียนทุน Erasmus Mundus สาขา Nanoscience and Nanotechnology ความเชี่ยวชาญพิเศษด้านการคำนวนเชิงควอนตัม ปัจจุบันเป็นนักศึกษาของมหาวิทยาลัย KU Leuven ประเทศเบลเยียม และ Chalmers University of Technology ประเทศสวีเดน ที่ปรึกษางานวิจัยได้แก่ Gustav Andersson และ Professor Per Delsing งานวิจัยนี้ทำที่ห้องปฏิบัติการ Quantum Technology สังกัด Chalmers University of Technology และ Wallenberg Center for Quantum Technology (WACQT) ประเทศสวีเดน

## คำสำคัญ

คอมพิวเตอร์ควอนตัมแบบสภาพนำยวดยิ่ง, วงจรควอนตัม, ระบบสองสถานะ, เครื่องสะท้อนคลื่นพื้นผิว, การแปรปรวนของความถี่สั่นพ้อง 

## บทคัดย่อ

คอมพิวเตอร์ควอนตัมมีบทบาทสำคัญในการพัฒนาศักยภาพด้านการคำนวนและแก้ปัญหาที่มีความซับซ้อนสูง การสร้างคอมพิวเตอร์ควอนตัมจึงเป็นงานวิจัยที่ได้รับความสนใจอย่างมากในปัจจุบัน หน่วยความจำที่เล็กที่สุดของคอมพิวเตอร์ควอนตัมเรียกว่า คิวบิต (qubit) การสร้างคิวบิตนั้นสามารถทำได้หลายวิธี หนึ่งในวิธีที่ได้รับความนิยมคือ การสร้างคิวบิตจากตัวนำสภาพยิ่งยวด (superconducting qubit) เนื่องจากสามารถสร้างได้ครั้งละมากๆและสามารถใช้ระบบควบคุมที่มีอยู่แล้วในปัจจุบัน อย่างไรก็ตาม การใช้คิวบิตจากตัวนำสภาพยิ่งยวดนั้น มีข้อจำกัดคือ การสูญเสียพลังงานจากอันตรกิริยาของคิวบิตและระบบสองสถานะ (two-level systems) ซึ่งเป็นสิ่งที่อยู่ในวัสดุที่ใช้ทำวงจรควอนตัม ปัจจุบันยังไม่มีคำอธิบายปรากฏการณ์ดังกล่าวได้อย่างชัดเจน การสูญเสียพลังงานจากอันตรกิริยานี้ จึงไม่สามารถหลีกเลี่ยงได้

งานวิจัยชิ้นนี้ศึกษาอันตรกิริยาของระบบสองสถานะ โดยใช้อุปกรณ์สะท้อนคลื่นพื้นผิว (surface acoustic wave resonator) ซึ่งสามารถเกิดการสั่นพ้องได้ ณ หลายความถี่ แทนการใช้อุปกรณ์สะท้อนคลื่นไมโครเวฟ (microwave resonator) ซึ่งเกิดการสั่นพ้องที่ความถี่เดียว ทำให้สามารถศึกษาอันตรกิริยาของระบบสองสถานะระหว่างความถี่ต่างๆพร้อมกันได้

จากการวัดสัญญาณคลื่นสะท้อนจากอุปกรณ์ในสภาพตัวนำยิ่งยวดและวิเคราะห์ข้อมูลพบว่า ความแปรปรวนของความถี่สั่นพ้อง ณ แต่ละความถี่ของอุปกรณ์ มีความสัมพันธ์กัน ทั้งนี้ค่าความสัมพันธ์ขึ้นอยู่กับความต่างของความถี่แต่ละคู่ และกำลังไฟฟ้าที่ใช้ขับอุปกรณ์ ผลการทดลองนี้สอดคล้องกับสมมติฐานของแบบจำลองระบบสองสถานะ (TLS model)

ผลที่ได้รับจากการวิจัย คือความเข้าใจอันตกิริยาระหว่างระบบสองสถานะกับวงจรควอนตัม ความรู้ดังกล่าวสามารถนำไปสู่การแก้ไขปัญหาความไม่เสถียรของคอมพิวเตอร์ควอนตัมแบบสภาพนำยวดยิ่ง อันเป็นหนึ่งในก้าวสำคัญของการสร้างควอนตัมคอมพิวเตอร์ชนิดดังกล่าว ประเทศไทยสามารถนำความรู้จากงานวิจัยนี้ มาช่วยสร้างและพัฒนาคอมพิวเตอร์ควอนตัม ซึ่งจะมีประโยชน์ต่อการคำนวนและแก้ปัญหาที่ซับซ้อนในงานวิจัยทุกสาขาในอนาคต