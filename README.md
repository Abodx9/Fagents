## Fagents
Fagents is a simple and efficient Python package designed to help you generate fake user-agent strings. This can be particularly useful for web scraping, testing, or any situation where you need to mimic different web browsers and devices.

### Features
- **Random User Agents**: Generate random user-agent strings for a variety of browsers and operating systems.
- **Specific User Agents**: Generate user-agent strings for specific browsers and operating systems including macOS, Opera, mobile devices, Linux, Windows, and Unix.
- **Easy to Use**: Simple and intuitive API for quick integration into your projects.

### Installation
To install the Fagents package, use pip:

```bash
pip install fagents
```

### Usage
Once installed, you can easily import and use the package in your Python projects:

```python
from fagents import xrand, Mac, opera, mobile, linux, win, unix

print(xrand())    # Generates a random user agent
print(Mac())      # Generates a user agent for macOS
print(opera())    # Generates a user agent for Opera browser
print(mobile())   # Generates a user agent for a mobile device
print(linux())    # Generates a user agent for a Linux system
print(win())      # Generates a user agent for a Windows system
print(unix())     # Generates a user agent for a Unix system
```

### Examples
Here are some examples of how you can use the Fagents package to generate fake user-agent strings:

```python
from fagents import Mac, opera, mobile

mac_user_agent = Mac()
print(f"Mac User Agent: {mac_user_agent}")

opera_user_agent = opera()
print(f"Opera User Agent: {opera_user_agent}")

mobile_user_agent = mobile()
print(f"Mobile User Agent: {mobile_user_agent}")
```

With Fagents, you can easily create realistic user-agent strings to simulate different browsers and operating systems, enhancing the flexibility and effectiveness of your web scraping and testing tasks.