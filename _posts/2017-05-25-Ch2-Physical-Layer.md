---
layout: post
title: "Physical Layer Notes"
subtitle: "Physical limitation of what can be sent over the transmission channel."
date: 2017-05-25 19:17:00
author: "8D"
header-img: 
comments: true
tags: 
published: true
---

## 2.1.1 Fourier Analysis
- A data signal can be handled by just imagining that it repeats the entire pattern over and over.

## 2.1.2 Bandwidth-Limited Signals
- Real channels affect different frequency signals differently.
- ASCII character "b" encoded in an 8-bit byte; bit pattern is 01100010.
- No transmission facility can transmit signals without losing some power in the process.
- Fourier components shows reduction in amplitude, not distorted.
	- Distortion is introduced due to transmission channels having different diminishing amplitudes.
	- Wire is usually undiminished from 0 up to some frequency (Hz).
- Width of the frequency range transmitted without being strongly attenuated is called **bandwidth**. 
	- Attenuated: reduce the amplitude of (a signal, electric current, or other oscillation).
- **Filters** are often used to further limit the bandwidth of a signal.
	- Example: 802.11 channels are allowed roughly up to 20 MHz, allowing more channels within the spectrum.
			- Signals that run from 0 up to a maximum frequency are called baseband signals.
			- Passband signals are signals that are shifted to occupy a higher range of frequencies.
            
## 2.1.2 Bandwidth-Limited Signals
- To electrical engineers, (analog) bandwidth is (as we have described above) a quantity measured in Hz. To computer scientists, (digital) bandwidth is the maximum data rate of a channel, a quantity measured in bits/sec.

## 2.1.3 The Maximum Data Rate of a Channel
- **SNR (Signal-to-Noise Ratio)**
	- Units of this log scale are called **decibles (dB)**.
    
## 2.2.1 Magnetic Tapes
- _Never underestimate the bandwidth of a station wagon full of tapes hurling down the highway.

## 2.2.2 Twisted Pairs
- A Twisted pair consists of two insulated copper wires, typically about 1 mm thick.
- Twisting is done because two parallel wires constitute a fine antenna.
	- The waves from different twists cancel out, so the wire radiates less effectively.
- A  signal is usually carried as the difference in voltage between the two wires in the pair.

## 2.2.5 Fiber Optics
- 50,000 Gbps
- Limited at 100 Gbps due to our inability to convert between electrical and optical signals faster.
- Multiple refraction requires a node for each ray. Fiber having this property is called multinode fiber.
- **Single-mode fiber** are more expensive and can be used for longer distances. 100 Gbps for 100 km without amplification.

## 2.3.1 The Electromagnetic Spectrum
- When an antenna of the appropriate size is attached to an electrical circuit, the electromagnetic waves can be broadcast efficiently and received by a receiver some distance away. All wireless communication is based on this principle.

## 2.3.2 Radio Transmission
- **Path loss** = radio waves losing power as grows distance from the source.

## 2.3.5 Light Transmission
- In difficult situations, an unguided optical link is needed.

## 2.4 COMMUNICATION SATELLITES
- Moon can be used as a satellite.
- Artificial satellites can amplify the signal before sending.
- **Transponder:** Listens to incoming signal.
- **Bent pipe:** A spectrum of a signal is rebroadcast to another frequency to avoid interference.

## 2.4.1 Geostationary Satellites
- Satellites are inherently broadcast media. Same cost to send to one or to thousands.
- Encryption is necessary to retain privacy.
- Cost of transmitting a message is independent of the distance traversed.

## 2.5 DIGITAL MODULATION AND MULTIPLEXING
- Digital Modulation: Process of converting between bits and signals.
