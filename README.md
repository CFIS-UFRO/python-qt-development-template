# Python Qt Development Template

Template to develop GUI applications based on Python and QT.

**Important note**: The development of this template is currently paused, but it will be resumed during the second semester of 2025.

# Releases

You can find the latest releases [here](https://github.com/CFIS-UFRO/python-qt-development-template/releases).

# Origin of this Template

Developing applications with graphical user interfaces (GUIs) is a common task in our laboratory, often needed for hardware control and data analysis projects.

To make these developments easier and more consistent, we developed standard project templates. This repository contains the template designed for building GUI applications using Python and Qt.

For those who prefer or require web technologies for their GUI applications, we also provide a specific template based on Electron, available at: https://github.com/CFIS-UFRO/electron-development-template.

# When to Choose This Template

This Python/Qt template is a good alternative for projects where **fast development** is important and a complex visual design is less critical than the core functionality. It's particularly useful for applications involving common tasks in science, such as **data analysis, data visualization, or communication with peripherals**. It is mainly indicated for tools used **within a lab or research environment**, and is not typically recommended for software intended for commercial distribution.

**Advantages**

A key benefit is the use of **Python and Qt**, technologies often used in scientific areas. This frequently means a **smoother learning curve** for development teams familiar with these tools. Additionally, Python has a **large collection of libraries** useful for scientific tasks, including mathematical computation, physics simulations, data analysis, communication with peripherals, and more.

**Disadvantages**

The main disadvantage of this approach is related with **distribution**. Making standalone applications that are easy for end-users to install and run can be more difficult compared to other methods. Because of this, the template isn't usually recommended **if the plan is to distribute the software widely outside the lab or sell it**.

**Alternative for Broader Distribution or High Visual Customization**

If **distributing a self-contained application easily to end-users** is important, or if a **highly customized visual appearance** is required, the template based on Electron/HTML/CSS might be a better fit: https://github.com/CFIS-UFRO/electron-development-template.