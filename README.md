# FSX.Wpf.Toolkit
WPF Toolkit and Controls Library

Commands

- RelayCommand - A slightly different flavor from DelegateCommand, providing the benefit of automatic evaluation of the canExecute predicate based on user input (mouse, keyboard).

Controls

- PaddedGrid - A smart way to add padding to Grid panel.
- WatermarkAdorner - A smart way to add watermark in TextBox.

  ```
  <AdornerDecorator>
      <TextBox ...>
          <fsx:WatermarkService.Watermark>
              <TextBlock>Watermark Text</TextBlock>
          </fsx:WatermarkService.Watermark>
      </TextBox>
  </AdornerDecorator>
  ```

**More controls coming soon, stay tuned...**
