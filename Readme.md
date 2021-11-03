# MUI - breakpoint, hover

``` javascript
<Button variant="contained" color="primary"
    sx={{
        color: 'primary.paper',
        bgcolor: {
            xxs: "red",
            xs: "orange",
            sm: "yellow",
            md: "#000000",
            lg: 'black',
            xl: "purple"
        },
        boxShadow: 'none',
        px: 4,
        ':hover': {
            bgcolor: 'success.main'
        }
    }}>
    Hell
</Button>

```