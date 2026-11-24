# Omarchy Weather

This standalone adaptation lives at [philipboldt/omarchy-weather](https://github.com/philipboldt/omarchy-weather) and is based on the built-in weather widget from [Omarchy](https://github.com/omacom/omarchy/tree/quattro/shell/plugins/panels/weather). It uses the local plugin ID `philip.weather` and takes the stock weather widget's place in the bar when enabled.

## Changes

- Right-click the weather icon to show or hide the current temperature. Omarchy saves your choice.
- On horizontal bars, the temperature appears to the left of the icon, in the same font and size as the battery percentage. The readout uses the same slot width as the battery widget to leave room beside the clock.
- The readout uses the weather popup's configured Celsius or Fahrenheit units. Left-click opens the forecast, and middle-click refreshes it.

## Installation

With the Omarchy shell running, install and enable the plugin:

```sh
omarchy plugin add https://github.com/philipboldt/omarchy-weather.git --enable
```

Right-click the weather icon to turn on the temperature readout.

## License

MIT. See [LICENSE](LICENSE) for the upstream copyright notice.
