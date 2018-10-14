
## symfony 相关


#### form :
> 关于formtype hidden valid 不显示错误信息

	在formtype中添加 'error_bubbling'=>false 属性即可
	add('user', HiddenType::class, [
        'label' => '使用人',
        'attr' => [
            'class' => 'disposeUser'
        ],
		'error_bubbling' => false
    ])
