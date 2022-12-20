This is a restyled Ant design component: <a href="https://ant.design/components/select/" target="_blank">https://ant.design/components/select</a>. In the future, this component could be refactored to not rely on a 3rd party library. Fortunately, because it's abstracted in our own library, any apps that use this component will not need to change their implementations. 

Same props as Ant Design Select component, except: `props.size` expects `xs/sm/md/lg/xl` instead of `small/medium/large`.