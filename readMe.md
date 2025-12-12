# 🧪 7-Day Elixir Learning Guide

A comprehensive guide to learning Elixir and Phoenix from foundations to production-ready applications.

## 📖 Overview

This repository contains a complete 7-day intensive learning path for Elixir and the Phoenix Framework. Whether you're new to functional programming or an experienced developer looking to learn Elixir, this guide will take you from zero to building real-time web applications.

## 🎯 What You'll Learn

- **Functional Programming**: Immutability, pattern matching, and pure functions
- **Concurrency**: Lightweight processes and the actor model
- **OTP**: GenServers, Supervisors, and fault-tolerant systems
- **Phoenix Framework**: Building web applications and APIs
- **LiveView**: Real-time UIs without writing JavaScript
- **Database Integration**: Working with Ecto and PostgreSQL

## 📅 Course Structure

### 🟢 Day 1 — Elixir Foundations
- Installing Elixir and IEx
- Basic syntax and data types
- Immutability and pattern matching
- Modules and functions

### 🟢 Day 2 — Control Flow & Recursion
- Conditionals (if, case, cond)
- Anonymous functions
- Function guards
- Recursive algorithms

### 🟢 Day 3 — Data Structures & Algorithms
- Lists, Maps, and Tuples
- Enum and Stream modules
- Common algorithms in Elixir
- Functional data manipulation

### 🟢 Day 4 — Concurrency & OTP
- Processes and message passing
- GenServer for state management
- Supervisors for fault tolerance
- Building resilient systems

### 🟢 Day 5 — Phoenix Fundamentals
- Creating Phoenix projects
- MVC architecture
- Routing and controllers
- Building JSON APIs

### 🟢 Day 6 — Phoenix LiveView
- Real-time UIs with LiveView
- State management
- Event handling
- PubSub for broadcasting

### 🔵 Day 7 — Full Project
Build a **Real-Time Task Board** with:
- Live updates across users
- CRUD operations
- Drag-and-drop functionality
- Database persistence

## 🚀 Getting Started

### Prerequisites

- Basic programming knowledge
- A computer with internet access
- Terminal/command line familiarity

### Installation

1. **Install Elixir**
   ```bash
   # macOS
   brew install elixir

   # Ubuntu/Debian
   sudo apt-get install elixir

   # Windows
   choco install elixir
   ```

2. **Install Phoenix**
   ```bash
   mix archive.install hex phx_new
   ```

3. **Verify Installation**
   ```bash
   elixir --version
   mix phx.new --version
   ```

## 📚 Repository Contents

```
├── guide.pdf              # Complete PDF learning guide
├── examples/              # Code examples for each day
│   ├── day1/
│   ├── day2/
│   ├── day3/
│   ├── day4/
│   ├── day5/
│   ├── day6/
│   └── day7/
├── exercises/             # Practice exercises with solutions
└── project/               # Final project: Real-Time Task Board
```

## 💻 Running the Examples

```bash
# Navigate to any day's examples
cd examples/day1

# Run Elixir files
elixir example.exs

# Or start IEx with the file loaded
iex example.exs
```

## 🎓 Final Project

The course culminates in building a **Real-Time Task Board** with features like:

- ✅ Create, update, and delete tasks
- ✅ Move tasks between columns (To Do → In Progress → Done)
- ✅ Real-time synchronization across all connected users
- ✅ Persistent storage with PostgreSQL
- ✅ Clean architecture using Phoenix contexts

### Running the Project

```bash
cd project/task_board

# Install dependencies
mix deps.get

# Create database
mix ecto.create
mix ecto.migrate

# Start Phoenix server
mix phx.server

# Visit http://localhost:4000
```

## 📖 Additional Resources

### Official Documentation
- [Elixir Docs](https://elixir-lang.org/docs.html)
- [Phoenix Framework](https://hexdocs.pm/phoenix)
- [Phoenix LiveView](https://hexdocs.pm/phoenix_live_view)
- [Ecto](https://hexdocs.pm/ecto)

### Books
- **Programming Elixir ≥ 1.6** by Dave Thomas
- **Elixir in Action** by Saša Jurić
- **Programming Phoenix LiveView** by Bruce Tate

### Online Learning
- [Elixir School](https://elixirschool.com) - Free tutorials
- [Exercism Elixir Track](https://exercism.org/tracks/elixir) - Practice exercises
- [ElixirForum](https://elixirforum.com) - Community support

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### How to Contribute

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Practice Exercises

Each day includes practice exercises to reinforce your learning:

- **Day 1**: Pattern matching, map manipulation, tuple operations
- **Day 2**: Factorial, Fibonacci, recursive algorithms
- **Day 3**: List operations, word counting, binary search
- **Day 4**: Process communication, GenServer implementation
- **Day 5**: REST API endpoints, JSON responses
- **Day 6**: LiveView forms, real-time counters
- **Day 7**: Complete task board application

## 🎯 Learning Outcomes

After completing this guide, you will be able to:

- ✅ Write idiomatic Elixir code using functional programming principles
- ✅ Build concurrent and fault-tolerant systems with OTP
- ✅ Create web applications and APIs with Phoenix
- ✅ Develop real-time features using Phoenix LiveView
- ✅ Work with databases using Ecto
- ✅ Deploy production-ready Elixir applications

## 💡 Tips for Success

1. **Practice Daily**: Dedicate at least 2-3 hours each day
2. **Type Everything**: Don't copy-paste, type out all examples
3. **Experiment**: Modify examples and see what happens
4. **Ask Questions**: Join ElixirForum and the community Slack
5. **Build Projects**: Apply what you learn in small projects

## 🌟 Next Steps

After completing this 7-day guide:

1. **Week 2**: Deep dive into OTP patterns
2. **Month 1**: Build a production application
3. **Month 2**: Learn distributed Elixir
4. **Month 3**: Explore GraphQL with Absinthe
5. **Ongoing**: Contribute to open source projects

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👏 Acknowledgments

- The Elixir Core Team for creating an amazing language
- The Phoenix Team for the incredible framework
- The Elixir community for being welcoming and helpful
- All contributors to this learning guide

## 📞 Contact & Support

- **Issues**: Open an issue on GitHub
- **Discussions**: Join [ElixirForum](https://elixirforum.com)
- **Slack**: [Elixir Slack Community](https://elixir-slack.community)
- **Twitter**: Follow [@elixirlang](https://twitter.com/elixirlang)

---

**⭐ If you find this guide helpful, please star the repository!**

Made with ❤️ for the Elixir community

*Happy Learning! 🚀*