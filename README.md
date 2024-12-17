# **AUDIO SPECTRUM VISUALIZER**

## **Theory**
Humans can hear sound ranging from approximately **20 Hz to 20 kHz**, a range known as the human auditory spectrum. An audio spectrum visualizer displays the prevalence of specific frequency ranges within audio input.

- **Low frequencies** (e.g., bass) appear as **larger bars on the left** of the display.  
- **High frequencies** (e.g., treble) appear as **larger bars on the right** of the display.  

The human auditory system perceives frequencies **non-linearly**, as shown in the figure below:

<img width="369" alt="Human auditory nonlinearity" src="https://github.com/user-attachments/assets/6be40ebc-33ff-4e00-a7e5-e8b2b483d0e2" />

---

## **Project Overview**
This project involves designing an **analog filter bank** to split the audio spectrum into discrete frequency bins. The filtered audio spectrum is then visualized on a **large LED matrix** driven by an **ESP32 microcontroller**.

### **Steps Involved**
1. **Analog Filter Design**: Built to isolate different frequency ranges.
2. **LED Matrix Visualization**: Connected and controlled via the ESP32.
3. **Waveform Generation and Testing**: Verified system functionality using generated waveforms.
4. **Soldered Circuit Assembly**: Ensured robust hardware integration for long-term performance.

---

## **Visual Results**

### **LED Matrix Output**
<img width="753" alt="LED Matrix Visualization" src="https://github.com/user-attachments/assets/5367b80d-0b05-4185-9a98-bbd48f99ce81" />
<img width="712" alt="LED Matrix Display" src="https://github.com/user-attachments/assets/dc6c7d82-5743-428e-bbfb-8c7d8a97fdc7" />

### **Waveform Generator Results**
<img width="718" alt="Waveform Results 1" src="https://github.com/user-attachments/assets/2d9bfa57-33c3-4647-a41e-8e21a7f2fc0a" />
<img width="612" alt="Waveform Results 2" src="https://github.com/user-attachments/assets/12f86263-5e71-4738-859e-401cea8f4b45" />
<img width="793" alt="Waveform Results 3" src="https://github.com/user-attachments/assets/01898a63-ce60-49ea-98b8-0105b36f8fdf" />
<img width="760" alt="Waveform Results 4" src="https://github.com/user-attachments/assets/0859486b-dc42-4c8a-bbf8-f4d6761cc1ce" />

### **Soldered Circuit**
<img width="683" alt="Soldered Circuit" src="https://github.com/user-attachments/assets/6de0a5b2-79f3-4d0f-b0b4-8178ef6cfe28" />

---

## **Technologies and Tools**
- **Hardware**: ESP32, Analog Filters, LED Matrix
- **Software**: Embedded C for ESP32 programming
- **Tools**: Digital multimeter, Oscilloscope, Soldering station

---

## **Key Features**
- Real-time visualization of audio frequency spectrum.  
- Accurate splitting of the spectrum into discrete bins.  
- Integration of analog filters with LED matrix for display.  
- Portable and responsive design using the ESP32 microcontroller.  

---

## **Future Improvements**
- Implementing FFT (Fast Fourier Transform) for more accurate frequency analysis.  
- Adding user input controls for dynamic customization.  
- Enhancing LED matrix resolution for finer visual detail.  

---

