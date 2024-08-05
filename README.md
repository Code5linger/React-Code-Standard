# React Code Standard

React Code Standard

# 1 Use `<React.StrictMode>`

<React.StrictMode>
<App />
</React.StrictMode>

# What dose it do?

During Development It render our component twice in order to find bugs, meanwhile React will check if we are using outdated parts of react API.

# Impact

Every console.log will be printed twice.

# 2 ⚠️ ISSUE - Changes not being updated

    1. Make Sure the application is actually running
    2. Stop the app & then restart it

    # Standard Practice:
        Always Keep VS Code's Teminal & Browsers Console Open

# 3 🧰 Tools

    1. VS Code - ES Lint

# 4 〽️ Alternatives

    Functions
        function Header() {}
        -OR-
        const Header = () => {}

    State Update
        () => setIsOpen(!isOpen)    // Meh
        -TO-
        () => setIsOpen((is) => !is)    // Better

        setStep(step - 1)   // Meh
        -TO-
        setStep((currentStep) => currentStep - 1)

    Refactor
        Every Components should have it's own file
            Use VS Codes refactor tool

# 5 ⏹️Tasks

    Identify Each Type of component


    [1-U-TURC23RR][🥈]
    [1-U-TURC23RR][Basic]
    [1-U-TURC23RR][Debugging]
    [1-U-TURC23RR][Components]
    [1-U-TURC23RR][JSX]
    [1-U-TURC23RR][JSinReact]
    [1-U-TURC23RR][Props]

16.25 + 6 + 1.125 + 19.5 + 7.5 + 2 + 
