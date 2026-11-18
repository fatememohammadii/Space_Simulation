<div align="center">

# 🚀 OrbitLab
### Physics experiments across the Solar System

**One program. Nine experiments. Eight planets.**  
Explore how gravity changes the results of everyday physics experiments — from free fall to elevator motion.

<br>

![C](https://img.shields.io/badge/Language-C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)
![Physics](https://img.shields.io/badge/Topic-Physics-6C63FF?style=for-the-badge)
![Planets](https://img.shields.io/badge/Planets-8-F4B942?style=for-the-badge)

</div>

---

## 🌌 About the project

What happens if you drop an object on Jupiter instead of Earth? How high would it rise on Mars? Would a pendulum swing at the same speed on the Moon's neighboring planets?

**OrbitLab** is a menu-driven C application that lets you explore these questions through nine basic physics experiments. Enter the required values, choose an experiment, and compare the calculated results across eight planets using their gravitational acceleration values.

The goal is to make physics more interactive while practicing core C programming concepts such as functions, arrays, pointers, loops, conditional statements, and user input.

## 🪐 The planetary dataset

The program includes gravitational acceleration values for:

| Planet | Gravitational acceleration (m/s²) |
|---|---:|
| Mercury | 3.70 |
| Venus | 8.87 |
| Earth | 9.81 |
| Mars | 3.71 |
| Jupiter | 24.79 |
| Saturn | 10.44 |
| Uranus | 8.69 |
| Neptune | 11.15 |

## 🧪 The experiment menu

Choose from nine calculations:

| # | Experiment | What it calculates |
|---:|---|---|
| 1 | Free Fall | Distance fallen over a given time |
| 2 | Vertical Upward Throw | Maximum height reached from an initial speed |
| 3 | Weight | Gravitational force acting on a given mass |
| 4 | Gravitational Potential Energy | Potential energy at a given height |
| 5 | Hydrostatic Pressure | Pressure at a given liquid depth |
| 6 | Archimedes' Buoyant Force | Buoyant force on an immersed volume |
| 7 | Simple Pendulum | Pendulum period for a given length |
| 8 | Fixed-Rope Tension | Tension calculated as mass multiplied by gravity |
| 9 | Elevator Experiment | Apparent weight for the selected acceleration direction |

Each experiment uses the same input values to calculate and display a result for all eight planets.

## 📐 Physics formulas

The program uses the following equations:

| Experiment | Formula |
|---|---|
| Free fall | \(h = \frac{1}{2}gt^2\) |
| Maximum height | \(h_{max} = \frac{v_0^2}{2g}\) |
| Weight | \(W = mg\) |
| Potential energy | \(E_p = mgh\) |
| Hydrostatic pressure | \(P = \rho gh\) |
| Buoyant force | \(F_b = \rho gV\) |
| Simple pendulum | \(T = 2\pi\sqrt{\frac{L}{g}}\) |
| Fixed-rope tension | \(F = mg\) |
| Elevator (upward acceleration) | \(N = m(g+a)\) |
| Elevator (downward acceleration) | \(N = m(g-a)\) |

Here, \(g\) is the gravitational acceleration of the selected planet.

## 🧰 C concepts practiced

- **Functions:** Each experiment is implemented as a separate function.
- **Arrays:** Planet names and gravitational acceleration values are stored in arrays.
- **Pointers:** The experiment functions receive the gravity array through a pointer.
- **Loops:** The program iterates through all eight planets to calculate results.
- **Switch-case:** The menu routes the user's selection to the corresponding experiment.
- **Input handling:** `scanf()` is used to collect experiment values and menu choices.
- **Math library:** `sqrt()` is used for the simple pendulum calculation.

## ⚙️ Run the program

### Requirements

- A C compiler, such as GCC
- The C standard library
- The math library (`libm` on systems that require explicit linking)

### Compile

Save the source code as `main.c`, then compile it with:

```bash
gcc main.c -o orbitlab -lm
```

### Execute

On macOS or Linux:

```bash
./orbitlab
```

On Windows:

```bash
orbitlab.exe
```

## 🖥️ Using the program

1. Enter the scientist's name when prompted.
2. Select an experiment from the menu.
3. Enter the requested physical quantities.
4. View the calculated results for all eight planets.
5. Select another experiment or enter `-1` to exit.

## 🔭 Possible future improvements

- Add input validation for all experiment values.
- Support names containing spaces.
- Add more celestial bodies, such as Earth's Moon.
- Display results in a formatted comparison table.
- Allow users to choose a planet instead of calculating all eight every time.
- Add more physics experiments.

---

<div align="center">

**Built with C · Inspired by physics · Curious about the universe** 🌠

</div>
