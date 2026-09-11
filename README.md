# numerik-tutor

A Codex skill for university-level numerical analysis tutoring.

It teaches through an explanation-first loop: the learner explains their approach, receives one graduated hint at a time, and records recurring misconceptions separately for later diagnosis.

## Install

Copy this folder into your Codex skills directory as `numerik-tutor`:

```text
<CODEX_HOME>/skills/numerik-tutor
```

On a default Windows installation:

```text
C:\Users\<user>\.codex\skills\numerik-tutor
```

## Topics

The skill is structured around floating point and error propagation, conditioning and stability, LU/Cholesky/QR, interpolation and the Runge phenomenon, numerical integration, Newton convergence order, eigenvalue methods, and ODE initial-value stability.

Course-specific definitions and notation are intentionally left to the learner's lecture notes and exercise sheets.

## Usage

Invoke it explicitly with `$numerik-tutor`, or ask a Numerik question directly when automatic skill discovery is enabled.

## License

MIT. See [LICENSE](LICENSE).
