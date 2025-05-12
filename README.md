# Component Library SDK

This project implements Task 2 from the assignment: creating a simple component library/SDK using React and TypeScript, and using it to build a two-page demo application for generating a "Coding Conf" ticket.

The focus is on reusability, clean code, minimal redundancy, and adherence to the specified constraints (no external UI libraries, simple CSS with CSS Modules, TypeScript).


## Tech Stack

* **Framework:** React
* **Language:** TypeScript
* **Build Tool:** Vite
* **Styling:** CSS Modules (Simple CSS, no Tailwind or external UI libs)

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/manish8472/component-library-sdk-task.git
    cd component-library-sdk-task
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Start the development server:**
    ```bash
    npm run dev
    ```
    This will start the Vite development server, and you can access the application in your browser (usually at `http://localhost:5173`).

## How to use the Components

1. **Import the component:**
    ```typescript
    import Button from "../../components";
    import InputField from "../../components";
    // etc.
    ```
2. **Use the component:**
    ```jsx
    <Button
          type="submit"
          fullWidth
          varient="secondry"
        >
          {"Button-name"}
    </Button>
    ```
## How to run the demo 

### You do not need to run the demo. I have already deployed, so you can see it directly.

**Website Link: ** [https://component-library-sdk-task.vercel.app/](https://component-library-sdk-task.vercel.app/)


* **Component Reusability:** Components like `Button`, `InputField`, `Ticket`, `Logo`, `Text`, `Heading` and `Page_Layout` are designed to be reusable across different parts of the application (demonstrated in the two pages).

