# Traveling-wave-on-a-changing-string-density

A string is made from several pieces of string where each segment has a length L. Each segment is joined together end to end to make a combined string of length nL. The first piece of string has mass per unit length μ, the second piece has mass per unit length 2μ, and the third piece has mass per unit length 3μ, and the last piece has a mass per unit length nμ. The combined string is under tension T.
Write a computer program that will calculate the time it takes a transverse wave to travel the entire length of the string for the following cases: n = 10, 100, 1000, 10000 (assume μ has a value of 1 kg/m, T = 1 N, and L = 1m).

μ   2μ   3μ       nμ
L    L    L   ...  L

Δt = L √(T/μ) (√1 + √2 + √3 + ... + √n)

Δt ≈ (2/3) * (nL/√(T/μ)) * n^(1/2)
