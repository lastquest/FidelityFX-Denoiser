# FidelityFX Denoiser

Copyright (c) 2020 Advanced Micro Devices, Inc. All rights reserved.
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

## Overview

FidelityFX Denoiser will contain a collection of highly optimized denoiser implementations for specific use cases.

## FFX Reflection Denoiser

The reflection denoiser includes a high performant Spatio-temporal denoiser specialized for reflection denoising.
The preferred use case of this denoiser is within applications requiring denoised radiance values generated by some stochastic reflection implementation.
Example of stochastic reflections:
- Stochastic Screen Space Reflections
- Stochastic Raytraced Reflections

### Links

- ffx-reflection-dnsr contains the [Reflection Denoiser](https://github.com/GPUOpen-Effects/FidelityFX-Denoiser/tree/master/ffx-reflection-dnsr)
- Visit [FidelityFX SSSR](https://github.com/GPUOpen-Effects/FidelityFX-SSSR/tree/master/sample) to see the reflection denoiser in action.

## FFX Shadow Denoiser (Future Update)
A denoiser optimized for raytraced shadows will be added here in a future update. If you are a developer working on a raytracing title then please contact your AMD representative for early access.