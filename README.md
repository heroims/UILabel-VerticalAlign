UILabel-VerticalAlign
=====================

UILable 上对齐 下对齐

    UILabel *label=[[UILabel alloc] initWithFrame:CGRectMake(0, 0, 320, 200)];
    label.textAlignment=NSTextAlignmentLeft;
    label.font=[UIFont fontWithName:@"Helvetica" size:12];
    
    //上对齐
    [label alignTop];
    //下对齐
    [label alignBottom];
