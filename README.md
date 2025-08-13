# MCP-Calculator-Server
A minimal, production-ready Model Context Protocol (MCP) server that exposes a collection of math utilities (arithmetic, trigonometry, algebra, number theory) via the Python MCP SDK’s FastMCP (mcp.server.fastmcp.FastMCP).

## Features

Simple, readable implementation using FastMCP

16+ tools covering common calculator operations

Safe input validation with helpful error messages

Works with MCP Inspector, Claude Desktop, and any MCP-compatible client

Transport: stdio

## Available Tools

The following tools are available for AI agents to call:
- add(a: int, b: int) -> int: Add two numbers.
- sub(a: int, b: int) -> int: Subtract two numbers.
- mul(a: int, b: int) -> int: Multiply two numbers.
- div(a: int, b: int) -> float: Divide two numbers (returns floating point).
- power(base: float, exponent: float) -> float: Raise a number to a power.
- square_root(x: float) -> float: Calculate the square root of a number.
- factorial(n: int) -> int: Calculate the factorial of a non-negative integer.
- log(x: float, base: float = math.e) -> float: Calculate logarithm with optional base.
- sin(x: float) -> float: Calculate sine of an angle in radians.
- cos(x: float) -> float: Calculate cosine of an angle in radians.
- tan(x: float) -> float: Calculate tangent of an angle in radians.
- degrees_to_radians(degrees: float) -> float: Convert degrees to radians.
- radians_to_degrees(radians: float) -> float: Convert radians to degrees.
- gcd(a: int, b: int) -> int: Calculate greatest common divisor.
- lcm(a: int, b: int) -> int: Calculate least common multiple.
- is_prime(n: int) -> bool: Check if a number is prime.
- quadratic_roots(a: float, b: float, c: float) -> tuple: Solve quadratic equation ax² + bx + c = 0.
