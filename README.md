# Admin Dashboard 
- used react, material UI - https://mui.com/material-ui/getting-started/installation/
- react-pro-sidebar - to create sidebar easily - https://www.npmjs.com/package/react-pro-sidebar
- react-router-dom@6 - for routing https://v5.reactrouter.com/web/guides/quick-start
- @mui/x-data-grid - https://mui.com/x/react-data-grid/getting-started/
- @mui/icons-material - for icons
- formik - form library - https://formik.org/docs/overview
- yup - validation library - https://www.npmjs.com/package/yup
- formcalender - for calender - https://fullcalendar.io/docs/initialize-es6
- nivo-charts - https://nivo.rocks/ - for charts, In their website you can go and click and follow steps to add any type of chart you want, we have used `@nivo/core @nivo/pie @nivo/line @nivo/bar @nivo/geo`
- used google fonts - Source Sans Pro

- whole cmd - `npm install @mui/material @emotion/react @emotion/styled @mui/x-data-grid @mui/icons-material react-router-dom@6 react-pro-sidebar formik yup @fullcalendar/core @fullcalendar/daygrid @fullcalendar/timegrid @fullcalendar/list @nivo/core @nivo/pie @nivo/line @nivo/bar @nivo/geo`


## Data
- mockGeoFeatures.js - for neo-charts data
- mockData.js

## Folder structure
- components folder - have components which are used in more than one place, like graphs
- scenes 
    - dashboard - contains dashboard
    - global - contains Topbar & Sidebar which is commmon in all globally
- theme.js - for typography and light/dark mode

## Extras
- used Tailwind shades extension for generating different shades of color, cmd+k and cmd+g