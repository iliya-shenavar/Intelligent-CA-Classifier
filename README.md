# Intelligent CA Classifier

This project is a **Control Unit implementation** for a custom **Computer Architecture (CA)** system. It includes a complete hardware design flow from source files to bitstream generation, allowing simulation, synthesis, and FPGA deployment. The project was developed in **Xilinx ISE**, making it suitable for educational, experimental, or research purposes in digital logic design.

The Control Unit is responsible for orchestrating the execution of instructions within a processor by generating appropriate control signals based on input opcodes. This project serves as a solid foundation for understanding the inner workings of CPU control paths.

## 🧠 Features

- ✅ Designed using **Xilinx ISE Design Suite**
- ✅ Complete set of source, intermediate, and output files (.bit, .ngc, .prj, etc.)
- ✅ Suitable for **simulation, synthesis, and FPGA deployment**
- ✅ Modular and extensible for integration with other datapath components
- ✅ Useful for **Computer Architecture labs, FPGA enthusiasts, and embedded system learners**

## 📁 Project Structure

```
CA_pro/
├── Control/
│   ├── control_unit.bit      # Bitstream file ready for FPGA programming
│   ├── control_unit.ngc      # Netlist after synthesis
│   ├── control_unit.ngd      # Native Generic Database file
│   ├── control_unit.pcf      # Pin constraints file
│   ├── Control.xise          # Xilinx ISE project file
│   ├── *.cmd_log, *.twr, etc. # Log and report files
│   └── ...                   # Supporting synthesis/build artifacts
```

## 🤝 Collaborators

This project was developed collaboratively by:

- [Iliya Shenavar](https://github.com/iliya-shenavar)
- [Mojtaba Khaleghi](https://github.com/mojtabaKhaleghi12)

> We designed and tested this control unit together, combining our knowledge in hardware design and digital systems.

## 🚀 How to Run the Project

To build and deploy the design on an FPGA or simulate it:

1. **Open Project**:
   - Launch **Xilinx ISE Design Suite**.
   - Open the file `Control.xise` located in the `Control/` directory.

2. **Run Synthesis**:
   - Click on *Synthesize - XST* in the ISE flow navigator.

3. **Run Implementation**:
   - Execute *Implement Design* and then *Generate Programming File*.

4. **Program FPGA**:
   - Use the `.bit` file to program your FPGA using **iMPACT** or **Vivado Hardware Manager**.

5. **Optional Simulation**:
   - Add a testbench file and use ISim or ModelSim to simulate behavior.

## 💡 Educational Use

This project is ideal for:
- University-level **Computer Architecture** courses
- FPGA learning environments
- Demonstrations of **CPU control logic**
- Lab experiments for digital systems

## 📜 License

This project is released under the **MIT License** – open for use, learning, and collaboration.

---

Feel free to clone, fork, or contribute to improve the design!

