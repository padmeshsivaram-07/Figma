# Ex09 Event Registration Web Application
## Date:

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
Home page

import { useState } from "react";
import wp25219791 from "./wp2521979-1.png";

export const IphonePro = (): JSX.Element => {
  const [isHovered, setIsHovered] = useState(false);

  const handleRegisterClick = () => {
    console.log("Register button clicked");
  };

  return (
    <main className="bg-white overflow-hidden w-full min-w-[484px] min-h-[875px] relative">
      <img
        className="absolute top-0 left-0 w-[484px] h-[875px] aspect-[1.6] object-cover"
        alt="Football championship background with trophy"
        src={wp25219791}
      />

      <header className="absolute top-[34px] left-[39px] w-[432px] [text-shadow:0px_4px_4px_#00000040] [font-family:'Inter-Regular',Helvetica] font-normal text-white text-2xl tracking-[0] leading-[normal]">
        SAVEETHA ENGINEERING COLLEGE
      </header>

      <h1 className="absolute top-[118px] left-[111px] w-[326px] [font-family:'Inter-ExtraBold',Helvetica] font-extrabold text-[#ff0004] text-4xl tracking-[0] leading-[normal]">
        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;FOOTBALL CHAMPIONSHIP
      </h1>

      <div className="absolute top-[228px] left-[97px] w-[311px] h-[42px] bg-[#d9d9d966]" />

      <p className="absolute top-[239px] left-[120px] w-[454px] [font-family:'Inter-Bold',Helvetica] font-bold text-[#ff0000] text-[15px] tracking-[0] leading-[normal]">
        nirf ranked automnomous institution
      </p>

      <button
        className="absolute top-[789px] left-[100px] w-[261px] h-[63px] bg-[#10014c] shadow-[0px_4px_4px_#00000040,0px_4px_4px_#00000040] cursor-pointer transition-transform duration-200 hover:scale-105 active:scale-95"
        onClick={handleRegisterClick}
        onMouseEnter={() => setIsHovered(true)}
        onMouseLeave={() => setIsHovered(false)}
        aria-label="Register for Football Championship"
        type="button"
      >
        <span className="absolute top-[9px] left-[30px] w-[207px] [font-family:'Hurricane-Regular',Helvetica] font-normal text-white text-[40px] tracking-[0] leading-[normal] whitespace-nowrap">
          REGISTER
        </span>
      </button>
    </main>
  );
};


page 2

import { useState } from "react";
import image31 from "./image3-1.png";

export const IphonePro = (): JSX.Element => {
  const [username, setUsername] = useState("");
  const [password, setPassword] = useState("");

  const handleSubmit = (e: React.FormEvent) => {
    e.preventDefault();
    console.log("Form submitted:", { username, password });
  };

  return (
    <div className="bg-white w-full min-w-[451px] min-h-[900px] relative">
      <img
        className="absolute top-0 left-0 w-[451px] h-[900px] aspect-[1.78] object-cover"
        alt="Background"
        src={image31}
      />

      <div className="absolute top-0 left-0 w-[451px] h-[900px] bg-[#d9d9d980]" />

      <form onSubmit={handleSubmit} className="relative z-10">
        <div className="absolute top-[198px] left-[68px] w-[316px] h-[75px] bg-[#0004ff] shadow-[0px_4px_4px_#00000040,0px_4px_4px_#00000040]">
          <label htmlFor="username" className="sr-only">
            Username
          </label>
          <input
            id="username"
            type="text"
            value={username}
            onChange={(e) => setUsername(e.target.value)}
            placeholder="username"
            className="absolute top-[6px] left-[55px] w-[219px] h-[63px] [font-family:'Jaro-Regular',Helvetica] font-normal text-[#00000099] text-5xl tracking-[0] leading-[normal] bg-transparent border-0 outline-none placeholder:text-[#00000099]"
            aria-label="Username"
          />
        </div>

        <div className="absolute top-[426px] left-[68px] w-[310px] h-[71px] bg-[#0003c2] shadow-[0px_4px_4px_#00000040,0px_4px_4px_#00000040]">
          <label htmlFor="password" className="sr-only">
            Password
          </label>
          <input
            id="password"
            type="password"
            value={password}
            onChange={(e) => setPassword(e.target.value)}
            placeholder="password"
            className="absolute top-[6px] left-[53px] w-[225px] h-[59px] [font-family:'Jaro-Regular',Helvetica] font-normal text-[#000000b2] text-5xl tracking-[0] leading-[normal] bg-transparent border-0 outline-none placeholder:text-[#000000b2]"
            aria-label="Password"
          />
        </div>
      </form>
    </div>
  );
};

page 3

import FreeDownloadSoccerStadiumWallpaper1920X1200Notebook1 from "./1515869-free-download-soccer-stadium-wallpaper-1920x1200-notebook-1.png";
import image4 from "./image-4.png";

export const IphonePro = (): JSX.Element => {
  return (
    <main className="bg-white overflow-hidden w-full min-w-[484px] min-h-[900px] relative">
      <img
        className="absolute top-0 left-0 w-[484px] h-[900px] aspect-[1.6] object-cover"
        alt="Soccer stadium background"
        src={FreeDownloadSoccerStadiumWallpaper1920X1200Notebook1}
      />

      <div
        className="absolute top-0 left-0 w-[509px] h-[900px] bg-[#000000b2]"
        aria-hidden="true"
      />

      <header className="absolute top-[86px] left-[94px] w-[413px]">
        <h1 className="[font-family:'Jacques_Francois_Shadow-Regular',Helvetica] font-normal text-white text-5xl tracking-[0] leading-[normal]">
          BOOK NOW
        </h1>
      </header>

      <div className="absolute top-[215px] left-[155px] w-[173px] h-[173px]">
        <img
          className="w-full h-full aspect-[1] object-cover"
          alt="Saveetha Engineering College logo"
          src={image4}
        />
      </div>

      <footer className="absolute top-[864px] left-[136px]">
        <p className="[font-family:'Jacques_Francois_Shadow-Regular',Helvetica] font-normal text-white text-sm tracking-[0] leading-[normal]">
          The offside law will not apply.
        </p>
      </footer>

      <section className="absolute top-[469px] left-12">
        <p className="[font-family:'Jacques_Francois_Shadow-Regular',Helvetica] font-normal text-white text-sm tracking-[0] leading-[normal]">
          book faster with your team name and details&nbsp;&nbsp;with proff
        </p>
      </section>
    </main>
  );
};
```


## OUTPUT:
![alt text](<Screenshot 2026-01-07 105334.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
