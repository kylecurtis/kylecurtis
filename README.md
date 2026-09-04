<table>
  <tr>
    <td valign="top" width="30%">
      <img alt="Me sitting at my first computer" src="https://github.com/user-attachments/assets/c54644f3-8273-4cc2-9b3d-76047482a59a" />
    </td>
    <td valign="top">

# Welcome! 👋

**My name is Kyle, and I am a C++ Software Engineer.**



  </td>
  </tr>
</table>

```cpp
#include <array>
#include <string_view>

struct About {
    std::string_view name{"Kyle Curtis"};

    constexpr auto interests = std::to_array<std::string_view>({
        "Linux", "Systems", "Security", "Graphics",
    });

    constexpr auto stack = std::to_array<std::string_view>({
        "C++", "Qt", "OpenGL", "CMake", "LLVM",
    });
};

constexpr About me{};
```
