# document-tailwind-screen



###  /** @type {import('tailwindcss').Config} */
###  module.exports = {
###  content: [
###    './src/pages/**/*.{js,ts,jsx,tsx,mdx}',
###    './src/components/**/*.{js,ts,jsx,tsx,mdx}',
###    './src/app/**/*.{js,ts,jsx,tsx,mdx}',
###  ],
###  theme: {
###    fontFamily: {
###      Assistant: ["Assistant", "sans-serif"],
###      OpenSans: ["OpenSans", "sans-serif"],
###      IBMPlexSans: ["IBMPlexSans", "sans-serif"],
###      Inter: ["Inter", "sans-serif"],
###      Poppinssemibold: ["poppins-semibold", "poppins", "sans-serif"],
###      InterExtraBold: ["InterExtraBold", "Inter"],
###      Pacifica: ["Pacifica", "Fantacy"],
###      PoppinsExtraLight: ["Poppins-ExtraLight"],
###      PoppinsRegular: ["PoppinsRegular"],
###      PoppinsExtraBold: ["Poppins-ExtraBold"],
###      FiraSansExtraBold: ["FiraSans-ExtraBold"],
###      FiraSansRegular: ["FiraSans-Regular"],
###      FiraSansLight: ["FiraSans-Light"],
###    },
###    screens: {
###      'xxs': "300px",
###      'xs': '340px',
###      'sm': '640px',
###      'md': '768px',
###      'lg': '1024px',
###      'xl': '1280px',
###      '2xl': '1536px',
###      '3xl': '1620px',
###      'laptop': "1444px",
###      'large': "1880px",
###    },

###    extend: {
###      backgroundImage: {
###        'gradient-radial': 'radial-gradient(var(--tw-gradient-stops))',
###        'gradient-conic':
###          'conic-gradient(from 180deg at 50% 50%, var(--tw-gradient-stops))',
###      },
###    },
###  },
###  plugins: [],
### }
